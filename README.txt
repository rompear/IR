INFORMATION:
Romeo Goosens (10424458), Jorn Ranzijn (11138610) and Joe Harrison (11770430)
romeogoosens94@gmail.com, jornranzijn@gmail.com, joeharrison1994@gmail.com


FILES:
-README.txt
- results/
"This folder contains all our results. It is structered in the following way"
    - results/
        - CBOW_EASY/ [baseline on easy model]
        - CBOW_HARD/ [baseline on hard model]
        - CBOW_PRE_EASY/ [CBOW on easy model]
        - CBOW_PRE_HARD/ [CBOW on hard model]
        - LSTM_PRE_EASY/ [LSTM on easy model]
        - LSTM_PRE_HARD/ [LSTM on hard model]
        - SEQ2SEQ_PRE_EASY/ [SEQ2SEQ on easy model]
        - SEQ2SEQ_PRE_HARD/ [SEQ2SEQ on hard model]

        All of the above folders contain corect and wrong image clssification / regression, structered as follows:
            - correct/
                top1/ [images that are in the top 1]
                top5/ [images that are in the top 5]
            - wrong/
                wrong images 
        
        Also Every folder contain loss and accuracy plots

- baseline.ipynb
"Notebook with the baseline approach"

- cbow.ipynb
"Notebook with the CBOW implementation"

- lstsm.ipynb
"Notebook with the LSTM implementation"

- plot_creator.ipynb 
"Notebook that loads the loss and accuracy of the models to make plots for all the models"

- query/ [Create this folder]
"Notebook where a query is given to the model and the images are orderd based on the query"

- Data/ [Create this folder]
"Here you should put the train, test and validation data"

- HARD/
    - IR_test_hard.json
    - IR_train_hard.json
    - IR_val_hard.json
- EASY/
    - IR_test_easy.json
    - IR_train_easy.json
    - IR_val_easy.json

- images/
"Here you should put the image features" 
- IR_image_features.h5
- IR_img_features2id.json

- environment.yml/
"Anaconda file for all our depency/libraries you to need for running the notebooks."


NOTE:
Contact us for more information about certain parts of code or if you need help running some parts.
