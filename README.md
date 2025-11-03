Brief Intro
-----------------
This file is an assignment from master program of Cultural Data & AI in University of Amsterdam. The file authors are Jiayi Zhu, Bowen Zhang, Xinyi Hu, Ahmet S.Sakrak and Xinran Zhang. This assignment aims to seek the insighful understanding of TikTokRefugee during the period of 'TikTok Ban' in 2025. The raw data is only about the first seven days of TikTokRefugee.
-----------------
This file contains the data and analysis results, including code, for the group project in the Data Project course of the Cultural Data & AI master's program at the University of Amsterdam.
The data is divided into raw data and clean data.
-	The raw data is stored in the file reddit_data.csv.
-	The clean data is stored in the file reddit_clean_data.csv.
-----------------
The code has been saved in 
-	Step_1_Data_mining.ipynb
-	Step_2_Coherence_Score.ipynb,
-	Step_3_Topic_Modeling_LDA_Mallet.ipynb,
-	Step_4_graphs.ipynb
All the code is written in Python.
The code and data results are all stored in HTML format.
-----------------
WARNING:
-	Due to the non-reproducibility of the LDA model, rerunning Topic_Modeling_LDA_Mallet.ipynb will retrain the model, which will result in differences between the newly generated analysis images and the original ones we used.
-	If you want to retrain the LDA model, in addition to replacing the data input and output paths in the Topic_Modeling_LDA_Mallet.ipynb file, you also need to update the Mallet file path in the mallet_path function.
-	The Mallet file path is located in the folder: ~/mallet-2.0.8/mallet-2.0.8/bin/mallet.
-	If you only need to repeat the data results, you only need to replace the model input path and result output path.
-	The model is stored in the PKL folder：dictionary.dict is the vocabulary collection generated during model training.
-	lda_model is the model we used in this analysis
-	ldamallet.pkl is a serialized (pickled) version of the trained LDA Mallet model which contains topic distributions, word-topic assignments, and all model parameters.
-	The remaining folders and files contain results generated from partial executions, including PNG, HTML, and other formats.
