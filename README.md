# From_Images_to_Social_Interactions_Understanding
The project was carried out as a master's thesis in collaboration with the Sorbonne université and the University of Trento, at the LIP6 and ISIR laboratories.  

My research question was: 

# How can we detect, analyze and understand social interactions from videos in order to create appropriate computational models ?

There are 6 files in this folder: 
- FFormationsDetectionAndAnalysis: The main programme in which F-Formations are calculated, taking time information into account. After detection, analyses were carried out concerning, distance, reciprocal angle and people's interest in the conversations.
- LSTMNextSpeakerPred: Prediction of the next speaker via LSTM, with a 40-second memory window.
- SVMRandomForestXGboostNextSpeakerPrediction: Prediction of the next speaker SVM, also trying other techniques such as Random and ForestXGboost.
- DatasetAnalysisSpeakingListening: Analysis on the dataset, on which actions are most often done before speaking and listening in turn changing, and analysis of the occurrence of labels in the dataset. 
- ParticipantsTracker: Tracking of the participants using MIL tracker that you iteratively initialise according to the number of people one wants to follow. 
- DetectionHaarHoughYOLO: Other Detection and tracking techniques tried.

Libraries to be imported: 
-  cv2
- csv
- matplotlib
- numpy 
- os
- sys
- tqdm
- pandas
- sklearn
- tensorflow 
- numpy 
- seaborn 
- warnings
- nbconvert
- scipy
- itertools
- xgboost
- collections
- glob
- random
