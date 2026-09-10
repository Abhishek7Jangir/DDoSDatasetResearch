# DDoSDatasetResearch
'''
│   README.md
│
├───AnonBooter
│   │   AE_CIAM_Binary_Final.keras
│   │   AE_Encoder_Extractor.keras
│   │   AE_Stage1_Full.keras
│   │   combiningAttackAndBenign.ipynb
│   │   preprocessing.ipynb
│   │   preprocessing_AnonBooter.ipynb
│   │   regression_imputer.pkl
│   │   RF_testing_with_Bot_IoT_HTTP.ipynb
│   │   RF_testing_with_Bot_IoT_TCP.ipynb
│   │   RF_testing_with_Bot_IoT_UDP.ipynb
│   │   RF_testing_with_Caida2007.ipynb
│   │   RF_testing_with_CIC2019TestingBinaryCleaned.ipynb
│   │   RF_testing_with_CIC2019TrainingBinary1.ipynb
│   │   RF_testing_with_CIC2019TrainingBinary2.ipynb
│   │   RF_testing_with_CICIDS2017.ipynb
│   │   RF_testing_with_CICIDS2018.ipynb
│   │   RF_testing_with_CTU13.ipynb
│   │   scaler.pkl
│   │   testing_Bot_IoT_HTTP-5Epoch.ipynb
│   │   testing_Bot_IoT_HTTP.ipynb
│   │   testing_BOT_IoT_TCP_DDoS-5Epochs.ipynb
│   │   testing_BOT_IoT_TCP_DDoS.ipynb
│   │   testing_BOT_IoT_UDP_DDoS-5Epochs.ipynb
│   │   testing_BOT_IoT_UDP_DDoS.ipynb
│   │   testing_Caida2007-5Epochs.ipynb
│   │   testing_Caida2007.ipynb
│   │   testing_CIC2017-5Epoch.ipynb
│   │   testing_CIC2017.ipynb
│   │   testing_CIC2019TestingData-5Epochs.ipynb
│   │   testing_CIC2019TestingData.ipynb
│   │   testing_CIC2019TrainingBinary1.ipynb
│   │   testing_CIC2019TrainingBinary2.ipynb
│   │   testing_CSC_CIC_2018-5Epochs.ipynb
│   │   testing_CSC_CIC_2018.ipynb
│   │   testing_CTU13-5Epoch.ipynb
│   │   testing_CTU13.ipynb
│   │   TrainingOnlyRandomForest_AnonBooter.ipynb
│   │   Training_AnonBooter-5Epoch.ipynb
│   │   Training_AnonBooter.ipynb
│   │
│   └───30EpochSavedFiles
│           AE_CIAM_Binary_Final.keras
│           AE_Encoder_Extractor.keras
│           AE_Stage1_Full.keras
│           regression_imputer.pkl
│           scaler.pkl
│
├───Balanced_ALL-TO-ONE
│   ├───booter
│   │   │   Labeled_Appender.ipynb
│   │   │   RF_testing_with_AnonBooter.ipynb
│   │   │   RF_testing_with_BoT-IoT-HTTP.ipynb
│   │   │   RF_testing_with_BoT-IoT-TCP.ipynb
│   │   │   RF_testing_with_BoT-IoT-UDP.ipynb
│   │   │   RF_testing_with_Caida.ipynb
│   │   │   RF_testing_with_CIC2017.ipynb
│   │   │   RF_testing_with_CIC2019TestingBinaryCleaned.ipynb
│   │   │   RF_testing_with_CIC2019TrainingBinary1.ipynb
│   │   │   RF_testing_with_CIC2019TrainingBinary2.ipynb
│   │   │   RF_testing_with_CICIDS2018.ipynb
│   │   │   RF_testing_with_CTU13.ipynb
│   │   │   TrainingOnlyRandomForest_Booter.ipynb
│   │   │
│   │   └───.ipynb_checkpoints
│   │           Labeled_Appender-checkpoint.ipynb
│   │           RF_testing_with_AnonBooter-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-HTTP-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-TCP-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-UDP-checkpoint.ipynb
│   │           RF_testing_with_Caida-checkpoint.ipynb
│   │           RF_testing_with_CIC2017-checkpoint.ipynb
│   │           RF_testing_with_CIC2019TestingBinaryCleaned-checkpoint.ipynb
│   │           RF_testing_with_CIC2019TrainingBinary1-checkpoint.ipynb
│   │           RF_testing_with_CIC2019TrainingBinary2-checkpoint.ipynb
│   │           RF_testing_with_CICIDS2018-checkpoint.ipynb
│   │           RF_testing_with_CTU13-checkpoint.ipynb
│   │           TrainingOnlyRandomForest_Booter-checkpoint.ipynb
│   │
│   ├───botiot
│   │   │   Labeled_Appender.ipynb
│   │   │   RF_testing_with_AnonBooter.ipynb
│   │   │   RF_testing_with_BoT-IoT-HTTP.ipynb
│   │   │   RF_testing_with_BoT-IoT-TCP.ipynb
│   │   │   RF_testing_with_BoT-IoT-UDP.ipynb
│   │   │   RF_testing_with_Caida.ipynb
│   │   │   RF_testing_with_CIC2017.ipynb
│   │   │   RF_testing_with_CIC2019TestingBinaryCleaned.ipynb
│   │   │   RF_testing_with_CIC2019TrainingBinary1.ipynb
│   │   │   RF_testing_with_CIC2019TrainingBinary2.ipynb
│   │   │   RF_testing_with_CICIDS2018.ipynb
│   │   │   RF_testing_with_CTU13.ipynb
│   │   │   TrainingOnlyRandomForest_BoT-IoT.ipynb
│   │   │
│   │   └───.ipynb_checkpoints
│   │           botiot-checkpoint.csv
│   │           Labeled_Appender-checkpoint.ipynb
│   │           RF_testing_with_AnonBooter-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-HTTP-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-TCP-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-UDP-checkpoint.ipynb
│   │           RF_testing_with_Caida-checkpoint.ipynb
│   │           RF_testing_with_CIC2017-checkpoint.ipynb
│   │           RF_testing_with_CICIDS2018-checkpoint.ipynb
│   │           RF_testing_with_CTU13-checkpoint.ipynb
│   │           TrainingOnlyRandomForest_BoT-IoT-checkpoint.ipynb
│   │
│   ├───caida
│   │   │   Labeled_Appender.ipynb
│   │   │   RF_testing_with_AnonBooter.ipynb
│   │   │   RF_testing_with_BoT-IoT-HTTP.ipynb
│   │   │   RF_testing_with_BoT-IoT-TCP.ipynb
│   │   │   RF_testing_with_BoT-IoT-UDP.ipynb
│   │   │   RF_testing_with_Caida.ipynb
│   │   │   RF_testing_with_CIC2017.ipynb
│   │   │   RF_testing_with_CIC2019TestingBinaryCleaned.ipynb
│   │   │   RF_testing_with_CIC2019TrainingBinary1.ipynb
│   │   │   RF_testing_with_CIC2019TrainingBinary2.ipynb
│   │   │   RF_testing_with_CICIDS2018.ipynb
│   │   │   RF_testing_with_CTU13.ipynb
│   │   │   TrainingOnlyRandomForest_Caida.ipynb
│   │   │
│   │   └───.ipynb_checkpoints
│   │           Labeled_Appender-checkpoint.ipynb
│   │           RF_testing_with_AnonBooter-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-HTTP-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-TCP-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-UDP-checkpoint.ipynb
│   │           RF_testing_with_Caida-checkpoint.ipynb
│   │           RF_testing_with_CIC2017-checkpoint.ipynb
│   │           RF_testing_with_CIC2019TestingBinaryCleaned-checkpoint.ipynb
│   │           RF_testing_with_CIC2019TrainingBinary1-checkpoint.ipynb
│   │           RF_testing_with_CIC2019TrainingBinary2-checkpoint.ipynb
│   │           RF_testing_with_CICIDS2018-checkpoint.ipynb
│   │           RF_testing_with_CTU13-checkpoint.ipynb
│   │           TrainingOnlyRandomForest_Caida-checkpoint.ipynb
│   │
│   ├───cic17
│   │   │   Labeled_Appender.ipynb
│   │   │   RF_testing_with_AnonBooter.ipynb
│   │   │   RF_testing_with_BoT-IoT-HTTP.ipynb
│   │   │   RF_testing_with_BoT-IoT-TCP.ipynb
│   │   │   RF_testing_with_BoT-IoT-UDP.ipynb
│   │   │   RF_testing_with_Caida.ipynb
│   │   │   RF_testing_with_CIC2017.ipynb
│   │   │   RF_testing_with_CIC2019TestingBinaryCleaned.ipynb
│   │   │   RF_testing_with_CIC2019TrainingBinary1.ipynb
│   │   │   RF_testing_with_CIC2019TrainingBinary2.ipynb
│   │   │   RF_testing_with_CICIDS2018.ipynb
│   │   │   RF_testing_with_CTU13.ipynb
│   │   │   TrainingOnlyRandomForest_CIC-IDS2017.ipynb
│   │   │
│   │   ├───.ipynb_checkpoints
│   │   │       Labeled_Appender-checkpoint.ipynb
│   │   │       RF_testing_with_AnonBooter-checkpoint.ipynb
│   │   │       RF_testing_with_BoT-IoT-HTTP-checkpoint.ipynb
│   │   │       RF_testing_with_BoT-IoT-TCP-checkpoint.ipynb
│   │   │       RF_testing_with_BoT-IoT-UDP-checkpoint.ipynb
│   │   │       RF_testing_with_Caida-checkpoint.ipynb
│   │   │       RF_testing_with_CIC2017-checkpoint.ipynb
│   │   │       RF_testing_with_CIC2019TestingBinaryCleaned-checkpoint.ipynb
│   │   │       RF_testing_with_CIC2019TrainingBinary1-checkpoint.ipynb
│   │   │       RF_testing_with_CIC2019TrainingBinary2-checkpoint.ipynb
│   │   │       RF_testing_with_CICIDS2018-checkpoint.ipynb
│   │   │       RF_testing_with_CTU13-checkpoint.ipynb
│   │   │       TrainingOnlyRandomForest_CIC-IDS2017-checkpoint.ipynb
│   │   │
│   │   └───CIC18FULL_Testing
│   │       │   RF_testing_with_CICIDS2018.ipynb
│   │       │   TrainingOnlyRandomForest_CIC-IDS2017.ipynb
│   │       │
│   │       └───.ipynb_checkpoints
│   │               RF_testing_with_CICIDS2018-checkpoint.ipynb
│   │               TrainingOnlyRandomForest_CIC-IDS2017-checkpoint.ipynb
│   │
│   ├───cic18
│   │   │   Labeled_Appender.ipynb
│   │   │   RF_testing_with_AnonBooter.ipynb
│   │   │   RF_testing_with_BoT-IoT-HTTP.ipynb
│   │   │   RF_testing_with_BoT-IoT-TCP.ipynb
│   │   │   RF_testing_with_BoT-IoT-UDP.ipynb
│   │   │   RF_testing_with_Caida.ipynb
│   │   │   RF_testing_with_CIC2017.ipynb
│   │   │   RF_testing_with_CIC2019TestingBinaryCleaned.ipynb
│   │   │   RF_testing_with_CIC2019TrainingBinary1.ipynb
│   │   │   RF_testing_with_CIC2019TrainingBinary2.ipynb
│   │   │   RF_testing_with_CICIDS2018.ipynb
│   │   │   RF_testing_with_CTU13.ipynb
│   │   │   TrainingOnlyRandomForest_CSE-CIC-IDS2018.ipynb
│   │   │
│   │   └───.ipynb_checkpoints
│   │           CIC18-checkpoint.csv
│   │           Labeled_Appender-checkpoint.ipynb
│   │           RF_testing_with_AnonBooter-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-HTTP-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-TCP-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-UDP-checkpoint.ipynb
│   │           RF_testing_with_Caida-checkpoint.ipynb
│   │           RF_testing_with_CIC2017-checkpoint.ipynb
│   │           RF_testing_with_CIC2019TestingBinaryCleaned-checkpoint.ipynb
│   │           RF_testing_with_CIC2019TrainingBinary1-checkpoint.ipynb
│   │           RF_testing_with_CIC2019TrainingBinary2-checkpoint.ipynb
│   │           RF_testing_with_CICIDS2018-checkpoint.ipynb
│   │           RF_testing_with_CTU13-checkpoint.ipynb
│   │           TrainingOnlyRandomForest_CSE-CIC-IDS2018-checkpoint.ipynb
│   │
│   ├───cic19
│   │   │   Labeled_Appender.ipynb
│   │   │   RF_testing_with_AnonBooter.ipynb
│   │   │   RF_testing_with_BoT-IoT-HTTP.ipynb
│   │   │   RF_testing_with_BoT-IoT-TCP.ipynb
│   │   │   RF_testing_with_BoT-IoT-UDP.ipynb
│   │   │   RF_testing_with_Caida.ipynb
│   │   │   RF_testing_with_CIC2017.ipynb
│   │   │   RF_testing_with_CIC2019TestingBinaryCleaned.ipynb
│   │   │   RF_testing_with_CIC2019TrainingBinary1.ipynb
│   │   │   RF_testing_with_CIC2019TrainingBinary2.ipynb
│   │   │   RF_testing_with_CICIDS2018.ipynb
│   │   │   RF_testing_with_CTU13.ipynb
│   │   │   testing_with_Anon_Booter.ipynb
│   │   │   testing_with_Caida2007.ipynb
│   │   │   testing_with_CTU13.ipynb
│   │   │   TrainingOnlyRandomForest_CIC-DDoS2019.ipynb
│   │   │   Training_CIC19.ipynb
│   │   │
│   │   └───.ipynb_checkpoints
│   │           Labeled_Appender-checkpoint.ipynb
│   │           RF_testing_with_AnonBooter-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-HTTP-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-TCP-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-UDP-checkpoint.ipynb
│   │           RF_testing_with_Caida-checkpoint.ipynb
│   │           RF_testing_with_CIC2017-checkpoint.ipynb
│   │           RF_testing_with_CIC2019TestingBinaryCleaned-checkpoint.ipynb
│   │           RF_testing_with_CIC2019TrainingBinary1-checkpoint.ipynb
│   │           RF_testing_with_CIC2019TrainingBinary2-checkpoint.ipynb
│   │           RF_testing_with_CICIDS2018-checkpoint.ipynb
│   │           RF_testing_with_CTU13-checkpoint.ipynb
│   │           testing_with_Anon_Booter-checkpoint.ipynb
│   │           testing_with_Caida2007-checkpoint.ipynb
│   │           testing_with_CTU13-checkpoint.ipynb
│   │           TrainingOnlyRandomForest_CIC-DDoS2019-checkpoint.ipynb
│   │           Training_CIC19-checkpoint.ipynb
│   │
│   ├───leave_booter
│   │   │   Labeled_Appender.ipynb
│   │   │   RF_testing_with_AnonBooter.ipynb
│   │   │   testing_with_Anon_Booter.ipynb
│   │   │   Training_leave_booter.ipynb
│   │   │   Training_RandomForest_leave_Booters.ipynb
│   │   │
│   │   └───.ipynb_checkpoints
│   │           Labeled_Appender-checkpoint.ipynb
│   │           RF_testing_with_AnonBooter-checkpoint.ipynb
│   │           testing_with_Anon_Booter-checkpoint.ipynb
│   │           Training_leave_booter-checkpoint.ipynb
│   │           Training_RandomForest_leave_AnonBooter-checkpoint.ipynb
│   │
│   ├───leave_BoT-IoT
│   │   │   Labeled_Appender.ipynb
│   │   │   RF_testing_with_BoT-IoT-HTTP.ipynb
│   │   │   RF_testing_with_BoT-IoT-TCP.ipynb
│   │   │   RF_testing_with_BoT-IoT-UDP.ipynb
│   │   │   testing_BOT_IoT_HTTP.ipynb
│   │   │   testing_BOT_IoT_TCP.ipynb
│   │   │   testing_BOT_IoT_UDP.ipynb
│   │   │   Training_leave_BoT-IoT.ipynb
│   │   │   Training_RandomForest_leave_BoT-IoT-DDoS.ipynb
│   │   │
│   │   └───.ipynb_checkpoints
│   │           Labeled_Appender-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-HTTP-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-TCP-checkpoint.ipynb
│   │           RF_testing_with_BoT-IoT-UDP-checkpoint.ipynb
│   │           testing_BOT_IoT_HTTP-checkpoint.ipynb
│   │           testing_BOT_IoT_HTTP1111-checkpoint.ipynb
│   │           testing_BOT_IoT_TCP-checkpoint.ipynb
│   │           testing_BOT_IoT_TCP_DDoS111-checkpoint.ipynb
│   │           testing_BOT_IoT_UDP-checkpoint.ipynb
│   │           testing_BOT_IoT_UDP_DDoS1111-checkpoint.ipynb
│   │           Training_leave_BoT-IoT-checkpoint.ipynb
│   │           Training_RandomForest_leave_BoT-IoT-DDoS-checkpoint.ipynb
│   │
│   ├───leave_Caida
│   │   │   Labeled_Appender.ipynb
│   │   │   RF_testing_with_Caida.ipynb
│   │   │   testing_with_Caida2007.ipynb
│   │   │   Training_leave_caida.ipynb
│   │   │   Training_RandomForest_leave_Caida2007.ipynb
│   │   │
│   │   └───.ipynb_checkpoints
│   │           Labeled_Appender-checkpoint.ipynb
│   │           RF_testing_with_Caida-checkpoint.ipynb
│   │           testing_with_Caida2007-checkpoint.ipynb
│   │           Training_leave_caida-checkpoint.ipynb
│   │           Training_RandomForest_leave_Caida2007-checkpoint.ipynb
│   │
│   ├───leave_CIC17
│   │   │   Labeled_Appender.ipynb
│   │   │   RF_testing_with_CIC2017.ipynb
│   │   │   testing_with_CICIDS2017.ipynb
│   │   │   Training_leave_cic17.ipynb
│   │   │   Training_RandomForest_leave_CIC-IDS2017.ipynb
│   │   │
│   │   └───.ipynb_checkpoints
│   │           Labeled_Appender-checkpoint.ipynb
│   │           RF_testing_with_CIC2017-checkpoint.ipynb
│   │           testing_with_CICIDS2017-checkpoint.ipynb
│   │           Training_leave_cic17-checkpoint.ipynb
│   │           Training_RandomForest_leave_CIC-IDS2017-checkpoint.ipynb
│   │
│   ├───leave_CIC18
│   │   │   Labeled_Appender.ipynb
│   │   │   RF_testing_with_CICIDS2018.ipynb
│   │   │   testing_with_CIC2018.ipynb
│   │   │   Training_leave_cic18.ipynb
│   │   │   Training_RandomForest_leave_CSE-CIC-IDS2018.ipynb
│   │   │
│   │   └───.ipynb_checkpoints
│   │           Labeled_Appender-checkpoint.ipynb
│   │           RF_testing_with_CICIDS2018-checkpoint.ipynb
│   │           testing_with_CIC2018-checkpoint.ipynb
│   │           testing_with_CIC20181111-checkpoint.ipynb
│   │           Training_leave_cic18-checkpoint.ipynb
│   │           Training_RandomForest_leave_CSE-CIC-IDS2018-checkpoint.ipynb
│   │
│   ├───leave_CIC19
│   │   │   Labeled_Appender.ipynb
│   │   │   RF_testing_with_CIC2019TestingBinaryCleaned.ipynb
│   │   │   RF_testing_with_CIC2019TrainingBinary1.ipynb
│   │   │   RF_testing_with_CIC2019TrainingBinary2.ipynb
│   │   │   testing_CIC2019TrainingBinary122.ipynb
│   │   │   testing_with_CIC2019TestingBinaryCleaned.ipynb
│   │   │   testing_with_Part1_CIC2019TrainingBinary.ipynb
│   │   │   testing_with_Part2_CIC2019TrainingBinary.ipynb
│   │   │   Training_leave_CIC19.ipynb
│   │   │   Training_RandomForest_leave_CIC-DDoS2019.ipynb
│   │   │
│   │   └───.ipynb_checkpoints
│   │           appendingFiles-checkpoint.ipynb
│   │           CTU-13-checkpoint.csv
│   │           Labeled_Appender-checkpoint.ipynb
│   │           RF_testing_with_CIC2019TestingBinaryCleaned-checkpoint.ipynb
│   │           RF_testing_with_CIC2019TrainingBinary1-checkpoint.ipynb
│   │           RF_testing_with_CIC2019TrainingBinary15555-checkpoint.ipynb
│   │           RF_testing_with_CIC2019TrainingBinary2-checkpoint.ipynb
│   │           testing_CIC2019TrainingBinary122-checkpoint.ipynb
│   │           testing_with_CIC2019TestingBinaryCleaned-checkpoint.ipynb
│   │           testing_with_CIC2019TrainingBinary15465-checkpoint.ipynb
│   │           testing_with_Part1_CIC2019TrainingBinary-checkpoint.ipynb
│   │           testing_with_Part2_CIC2019TrainingBinary-checkpoint.ipynb
│   │           Training_leave_CIC19-checkpoint.ipynb
│   │           Training_RandomForest_leave_CIC-DDoS2019-checkpoint.ipynb
│   │
│   └───leave_CTU13
│       │   Labeled_Appender.ipynb
│       │   RF_testing_with_CTU13.ipynb
│       │   testing_with_CTU13.ipynb
│       │   Training_leave_ctu.ipynb
│       │   Training_RandomForest_leave_CTU13.ipynb
│       │
│       └───.ipynb_checkpoints
│               Labeled_Appender-checkpoint.ipynb
│               RF_testing_with_CTU13-checkpoint.ipynb
│               testing_with_CTU13-checkpoint.ipynb
│               Training_leave_ctu-checkpoint.ipynb
│               Training_RandomForest_leave_CTU13-checkpoint.ipynb
│
├───BoT_IoT_DDoS
│       AE_Encoder_Extractor.keras
│       AE_Stage1_Full.keras
│       CIAM_CNN_Classifier.keras
│       CNNBOTIoTDDoS.ipynb
│       combiningAttackAndBenign.ipynb
│       preprocessingBotIot.ipynb
│       preprocessingCaida.ipynb
│       preprocessingCIC-DDoS2019TestingData.ipynb
│       preprocessingCICbenignDataset.ipynb
│       preprocessingCTU13.ipynb
│       regression_imputer.pkl
│       RF_testing_with_AnonBooter.ipynb
│       RF_testing_with_Caida2007.ipynb
│       RF_testing_with_CIC2019TestingBinaryCleaned.ipynb
│       RF_testing_with_CIC2019TrainingBinary1.ipynb
│       RF_testing_with_CIC2019TrainingBinary2.ipynb
│       RF_testing_with_CICIDS2017.ipynb
│       RF_testing_with_CICIDS2018.ipynb
│       RF_testing_with_CTU13.ipynb
│       scaler.pkl
│       testing_AnonBooter.ipynb
│       testing_Caida2007.ipynb
│       testing_CIC2017_Full.ipynb
│       testing_CSC_CIC_2018.ipynb
│       testing_CTU13.ipynb
│       testing_with_CIC2019TestingBinaryCleaned.ipynb
│       testing_with_CIC2019TestingData1.ipynb
│       testing_with_CIC2019TestingData2.ipynb
│       TrainingOnlyRandomForest_BoT-IoT-DDoS.ipynb
│       Training_BoT_IoT_DDoS.ipynb
│       Training_CIC-DDoS-2019.ipynb
│
├───CaidaDDoS2007
│   │   AE_CIAM_Binary_Final.keras
│   │   AE_Encoder_Extractor.keras
│   │   AE_Stage1_Full.keras
│   │   combiningAttackAndBenign.ipynb
│   │   preprocessing_CaidaDDoSCombinedBenign.ipynb
│   │   regression_imputer.pkl
│   │   RF_testing_with_AnonBooter.ipynb
│   │   RF_testing_with_Bot_IoT_HTTP.ipynb
│   │   RF_testing_with_Bot_IoT_TCP.ipynb
│   │   RF_testing_with_Bot_IoT_UDP.ipynb
│   │   RF_testing_with_CIC2019TestingBinaryCleaned.ipynb
│   │   RF_testing_with_CIC2019TrainingBinary1.ipynb
│   │   RF_testing_with_CIC2019TrainingBinary2.ipynb
│   │   RF_testing_with_CICIDS2017.ipynb
│   │   RF_testing_with_CICIDS2018.ipynb
│   │   RF_testing_with_CTU13.ipynb
│   │   scaler.pkl
│   │   testing_AnonBooter-5Epochs.ipynb
│   │   testing_AnonBooter.ipynb
│   │   testing_Bot_IoT_HTTP-5Epochs.ipynb
│   │   testing_Bot_IoT_HTTP.ipynb
│   │   testing_BOT_IoT_TCP_DDoS-5Epochs.ipynb
│   │   testing_BOT_IoT_TCP_DDoS.ipynb
│   │   testing_BOT_IoT_UDP_DDoS-5Epochs.ipynb
│   │   testing_BOT_IoT_UDP_DDoS.ipynb
│   │   testing_CIC2017-5Epochs.ipynb
│   │   testing_CIC2017.ipynb
│   │   testing_CIC2019TestingData-5Epochs.ipynb
│   │   testing_CIC2019TestingData.ipynb
│   │   testing_CIC2019Training1.ipynb
│   │   testing_CIC2019Training2.ipynb
│   │   testing_CSC_CIC_2018-5Epochs.ipynb
│   │   testing_CSC_CIC_2018.ipynb
│   │   testing_CTU13-5Epochs.ipynb
│   │   testing_CTU13.ipynb
│   │   TrainingOnlyRandomForest_Caida.ipynb
│   │   Training_Caida-5Epoch.ipynb
│   │   Training_Caida.ipynb
│   │
│   └───30EpochSavedFiles
│           AE_CIAM_Binary_Final.keras
│           AE_Encoder_Extractor.keras
│           AE_Stage1_Full.keras
│           regression_imputer.pkl
│           scaler.pkl
│
├───CIC-DDoS-2019
│   │   AE_Encoder_Extractor.keras
│   │   AE_Stage1_Full.keras
│   │   AutoEncoderCIC19.ipynb
│   │   CIAM_CNN_Classifier.keras
│   │   CNNCIC2019.ipynb
│   │   preprocessing-CIC2019_testing_server.ipynb
│   │   preprocessing.ipynb
│   │   preprocessingCIC-DDoS2019TestingData.ipynb
│   │   preprocessing_IoT_DDoS.ipynb
│   │   preprocessing_IoT_DDoS_HTTP.ipynb
│   │   regression_imputer.pkl
│   │   RF_testing_with_AnonBooter.ipynb
│   │   RF_testing_with_BoT-IoT-DDoS.ipynb
│   │   RF_testing_with_Bot_IoT_HTTP.ipynb
│   │   RF_testing_with_Bot_IoT_TCP.ipynb
│   │   RF_testing_with_Bot_IoT_UDP.ipynb
│   │   RF_testing_with_Caida2007.ipynb
│   │   RF_testing_with_CIC2019TestingBinaryCleaned.ipynb
│   │   RF_testing_with_CICIDS2017.ipynb
│   │   RF_testing_with_CICIDS2018.ipynb
│   │   RF_testing_with_CTU13.ipynb
│   │   scaler.pkl
│   │   testing_AnonBooter.ipynb
│   │   testing_BOT_IoT_DDoS.ipynb
│   │   testing_BOT_IoT_HTTP.ipynb
│   │   testing_BOT_IoT_TCP_DDoS.ipynb
│   │   testing_BOT_IoT_UDP_DDoS.ipynb
│   │   testing_Caida2007.ipynb
│   │   testing_CIC2017_Benign.ipynb
│   │   testing_CIC2017_Full.ipynb
│   │   testing_CSC_CIC_2018.ipynb
│   │   testing_CTU13.ipynb
│   │   testing_with_CIC2019TestingBinaryCleaned.ipynb
│   │   TrainingOnlyRandomForest_CIC-DDoS2019.ipynb
│   │   Training_CIC-DDoS-2019.ipynb
│   │   Training_CIC-ids-2017.ipynb
│   │
│   └───.ipynb_checkpoints
│           testing_AnonBooter-checkpoint.ipynb
│           testing_BOT_IoT_HTTP-checkpoint.ipynb
│           testing_Caida2007-checkpoint.ipynb
│           testing_CIC2017_Benign-checkpoint.ipynb
│           testing_CIC2017_Full-checkpoint.ipynb
│           testing_CTU13-checkpoint.ipynb
│           testing_with_CIC2019TestingBinaryCleaned-checkpoint.ipynb
│
├───CIC-IDS-2017
│   │   AdditionalCUrveGeneration.ipynb
│   │   AE_CIAM_Binary_Final.keras
│   │   AE_Encoder_Extractor.keras
│   │   AE_Stage1_Full.keras
│   │   HyperparameterTrainingOnlyRandomForest_CICIDS2017.ipynb
│   │   preprocessing.ipynb
│   │   regression_imputer.pkl
│   │   RF_testing_with_AnonBooter.ipynb
│   │   RF_testing_with_Bot_IoT_HTTP-experiment1.ipynb
│   │   RF_testing_with_Bot_IoT_HTTP.ipynb
│   │   RF_testing_with_Bot_IoT_TCP.ipynb
│   │   RF_testing_with_Bot_IoT_UDP.ipynb
│   │   RF_testing_with_Caida2007-experiment1.ipynb
│   │   RF_testing_with_Caida2007.ipynb
│   │   RF_testing_with_CIC2019TestingBinaryCleaned.ipynb
│   │   RF_testing_with_CIC2019TrainingBinary1.ipynb
│   │   RF_testing_with_CIC2019TrainingBinary2.ipynb
│   │   RF_testing_with_CICIDS2018.ipynb
│   │   RF_testing_with_CTU13.ipynb
│   │   scaler.pkl
│   │   testing_AnonBooter.ipynb
│   │   testing_Bot_IoT_HTTP.ipynb
│   │   testing_BOT_IoT_TCP_DDoS.ipynb
│   │   testing_BOT_IoT_UDP_DDoS.ipynb
│   │   testing_Caida2007.ipynb
│   │   testing_CSC_CIC_2018.ipynb
│   │   testing_CTU13.ipynb
│   │   testing_with_CIC2019TestingBinaryCleaned.ipynb
│   │   testing_with_CIC2019TrainingBinary1.ipynb
│   │   testing_with_CIC2019TrainingBinary2.ipynb
│   │   testing_with_CICIDS2017_COMBINED_DATASET_TESTING.ipynb
│   │   TrainingLogiRegression_CICIDS2017.ipynb
│   │   TrainingOnlyRandomForest_CICIDS2017.ipynb
│   │   TrainingRandomForest_CICIDS2017.ipynb
│   │   Training_CIC-IDS-2017.ipynb
│   │
│   └───.ipynb_checkpoints
│           AdditionalCUrveGeneration-checkpoint.ipynb
│           HyperparameterTrainingOnlyRandomForest_CICIDS2017-checkpoint.ipynb
│           testing_Bot_IoT_HTTP-checkpoint.ipynb
│           testing_CSC_CIC_2018-checkpoint.ipynb
│           testing_with_CICIDS2017_COMBINED_DATASET_TESTING-checkpoint.ipynb
│           TrainingLogiRegression_CICIDS2017-checkpoint.ipynb
│           TrainingOnlyRandomForest_CICIDS2017-checkpoint.ipynb
│           TrainingRandomForest_CICIDS2017-checkpoint.ipynb
│           Training_CIC_IDS_2017_888-checkpoint.ipynb
│
├───CSC_CIC_2018
│       AE_CIAM_Binary_Final.keras
│       AE_Encoder_Extractor.keras
│       AE_Stage1_Full.keras
│       CIAM_CNN_Classifier.keras
│       CNNCIC2018.ipynb
│       preprocessing.ipynb
│       regression_imputer.pkl
│       RF_testing_with_AnonBooter.ipynb
│       RF_testing_with_BoT-IoT-DDoS.ipynb
│       RF_testing_with_Caida2007.ipynb
│       RF_testing_with_CIC2019TestingBinaryCleaned.ipynb
│       RF_testing_with_CIC2019TrainingBinary.ipynb
│       RF_testing_with_CICIDS2017.ipynb
│       RF_testing_with_CTU13.ipynb
│       scaler.pkl
│       testing_AnonBooter.ipynb
│       testing_BOT_IoT_HTTP.ipynb
│       testing_BOT_IoT_TCP_DDoS.ipynb
│       testing_BOT_IoT_UDP_DDoS.ipynb
│       testing_Caida2007.ipynb
│       testing_CIC2017_Full.ipynb
│       testing_CTU13.ipynb
│       testing_with_CIC2019TestingBinaryCleaned.ipynb
│       testing_with_CIC2019TrainingBinary1.ipynb
│       testing_with_CIC2019TrainingBinary2.ipynb
│       TrainingOnlyRandomForest_CSE-CIC-IDS2018.ipynb
│       Training_CSC_CIC-2018.ipynb
│
├───CTU
│       AE_CIAM_Binary_Final.keras
│       AE_Encoder_Extractor.keras
│       AE_Stage1_Full.keras
│       combiningAttack&Benign.ipynb
│       regression_imputer.pkl
│       RF_testing_with_AnonBooter.ipynb
│       RF_testing_with_Bot_IoT_HTTP.ipynb
│       RF_testing_with_Bot_IoT_TCP.ipynb
│       RF_testing_with_Bot_IoT_UDP.ipynb
│       RF_testing_with_Caida2007.ipynb
│       RF_testing_with_CIC2019TestingBinaryCleaned.ipynb
│       RF_testing_with_CIC2019TrainingBinary1.ipynb
│       RF_testing_with_CIC2019TrainingBinary2.ipynb
│       RF_testing_with_CICIDS2017.ipynb
│       RF_testing_with_CICIDS2018.ipynb
│       scaler.pkl
│       testing_AnonBooter.ipynb
│       testing_Bot_IoT_HTTP.ipynb
│       testing_BOT_IoT_TCP_DDoS.ipynb
│       testing_BOT_IoT_UDP_DDoS.ipynb
│       testing_Caida2007.ipynb
│       testing_CIC2017.ipynb
│       testing_CIC2019TestingData.ipynb
│       testing_CIC2019TrainingData1.ipynb
│       testing_CIC2019TrainingData2.ipynb
│       testing_CSC_CIC_2018.ipynb
│       TrainingOnlyRandomForest_CTU13.ipynb
│       Training_CTU13.ipynb
│
├───leave_Anon_Booter
│       AE_Encoder_Extractor.keras
│       AE_Stage1_Full.keras
│       appendingFiles.ipynb
│       AutoEncoder_Training_leave_Anon_Booter.ipynb
│       CIAM_CNN_Classifier.keras
│       CNNCombineFileleave_Anon_Booter.ipynb
│       regression_imputer.pkl
│       RF_testing_with_AnonBooter.ipynb
│       scaler.pkl
│       testing_with_Anon_Booter.ipynb
│       Training_leave_Anon_BooTer.ipynb
│       Training_RandomForest_leave_AnonBooter.ipynb
│
├───leave_Bot_IoT_DDoS
│       AE_Encoder_Extractor.keras
│       AE_Stage1_Full.keras
│       CIAM_CNN_Classifier.keras
│       CNNCombineFileleave_BoT_IoT_DDoS.csv.ipynb
│       CombiningFiles.ipynb
│       regression_imputer.pkl
│       RF_testing_with_BoT-IoT-HTTP.ipynb
│       RF_testing_with_BoT-IoT-TCP.ipynb
│       RF_testing_with_BoT-IoT-UDP.ipynb
│       scaler.pkl
│       testing_BOT_IoT_HTTP.ipynb
│       testing_BOT_IoT_TCP_DDoS.ipynb
│       testing_BOT_IoT_UDP_DDoS.ipynb
│       testing_CTU13.ipynb
│       testing_with_CIC2019TestingBinaryCleaned.ipynb
│       Training_leave_BoT_IoT_DDoS_csv.ipynb
│       Training_RandomForest_leave_BoT-IoT-DDoS.ipynb
│
├───leave_Caida2007
│       AE_Encoder_Extractor.keras
│       AE_Stage1_Full.keras
│       appendingFiles.ipynb
│       AutoEncoder_Training_leave_Caida2007.ipynb
│       CIAM_CNN_Classifier.keras
│       CNNCombineFileleave_Caida2007.ipynb
│       regression_imputer.pkl
│       RF_testing_with_Caida.ipynb
│       scaler.pkl
│       testing_with_Caida2007.ipynb
│       Training_leave_Caida2007.ipynb
│       Training_RandomForest_leave_Caida2007.ipynb
│
├───leave_CIC_DDoS_2019
│       AE_Encoder_Extractor.keras
│       AE_Stage1_Full.keras
│       CIAM_CNN_Classifier.keras
│       CNNCombineFileleave_CIC_DDoS_2019.ipynb
│       CombiningFiles.ipynb
│       regression_imputer.pkl
│       RF_testing_with_CIC2019TestingBinaryCleaned.ipynb
│       RF_testing_with_CIC2019TrainingBinary1.ipynb
│       RF_testing_with_CIC2019TrainingBinary2.ipynb
│       scaler.pkl
│       splitCIC19InTwo.ipynb
│       testing_with_CIC2019TestingBinaryCleaned.ipynb
│       testing_with_Part1_CIC2019TrainingBinary.ipynb
│       testing_with_Part2_CIC2019TrainingBinary-Copy1.ipynb
│       Training_leave_CIC2019.ipynb
│       Training_RandomForest_leave_CIC-DDoS2019.ipynb
│
├───leave_CIC_IDS2017
│       AE_Encoder_Extractor.keras
│       AE_Stage1_Full.keras
│       appendingFiles.ipynb
│       AutoEncoder_Training_leave_CICIDS2017.ipynb
│       CIAM_CNN_Classifier.keras
│       CNNCombineFileleave_CICIDS2017.ipynb
│       regression_imputer.pkl
│       RF_testing_with_CIC2017.ipynb
│       scaler.pkl
│       testing_with_CICIDS2017.ipynb
│       Training_leave_CIC-IDS2017.ipynb
│       Training_RandomForest_leave_CIC-IDS2017.ipynb
│
├───leave_CSE_CIC_IDS2018
│       AE_Encoder_Extractor.keras
│       AE_Stage1_Full.keras
│       appendingFiles.ipynb
│       AutoEncoder_Training_leave_CSC_CIC_2018.ipynb
│       CIAM_CNN_Classifier.keras
│       CNNCombineFileleave_CSC_CIC_2018.ipynb
│       CombiningFiles.ipynb
│       regression_imputer.pkl
│       RF_testing_with_CICIDS2018.ipynb
│       scaler.pkl
│       testing_with_CIC2018.ipynb
│       Training_leave_CSC_CIC_2018.ipynb
│       Training_RandomForest_leave_CSE-CIC-IDS2018.ipynb
│
├───leave_CTU13
│       AE_Encoder_Extractor.keras
│       AE_Stage1_Full.keras
│       appendingFiles.ipynb
│       AutoEncoder_Training_leave_CTU13.ipynb
│       CIAM_CNN_Classifier.keras
│       CNNCombineFileleave_CTU13.ipynb
│       errorPrompt.txt
│       regression_imputer.pkl
│       RF_testing_with_CTU13.ipynb
│       scaler.pkl
│       testing_with_CTU13.ipynb
│       Training_leave_CTU13.ipynb
│       Training_RandomForest_leave_CTU13.ipynb
│
└───One-To-One_Labelwise_TrainingTesting
    │   Final_Cross_Corpus_Results.csv
    │   oneTOone_labelwise_TrainingTesting.ipynb
    │
    └───curves
            Curves_Train17_Test18_Botnet.png
            Curves_Train17_Test18_DoS_GoldenEye.png
            Curves_Train17_Test18_DoS_Hulk.png
            Curves_Train17_Test18_DoS_Slowhttptest.png
            Curves_Train17_Test18_DoS_Slowloris.png
            Curves_Train17_Test18_FTP_BruteForce.png
            Curves_Train17_Test18_SSH_BruteForce.png
            Curves_Train18_Test17_Botnet.png
            Curves_Train18_Test17_DoS_GoldenEye.png
            Curves_Train18_Test17_DoS_Hulk.png
            Curves_Train18_Test17_DoS_Slowhttptest.png
            Curves_Train18_Test17_DoS_Slowloris.png
            Curves_Train18_Test17_FTP_BruteForce.png
            Curves_Train18_Test17_SSH_BruteForce.png
'''
