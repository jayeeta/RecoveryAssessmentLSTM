# RecoveryAssessmentLSTM
In this project, an LSTM-AE model is trained to fit the GRF data of healthy walking gait. Then GRF data of patients with musculoskeletal impairments from GaitRec are used as test data. We analysed the loss value generated from the trained lstm-ae model for GRF data of different phases of recovery. The project has been done using ipython.
1. visualize_gaitrec.ipynb is used to visualize the gait pattern of the participants
2. lstmae_training.ipynb is used to fit the models using healthy controls data for three axes - vertical (V), anterior-posterior (AP), and mediolateral (ML) force components.
Note: there are center of presssure components as well
4. recovery_testing.ipynb is used to test the trained models with corresponding gait data of impaired patients acquired during different phases of recovery.

lstm_auto_080121_right_ML_84816en.h5 is added as a sample trained model file
