Code is present in report_code folder as 1.ipynb, 2.ipynb, 3.ipynb, 4.ipynb, 5.ipynb and 6.ipynb

1.ipynb -> Initial model with Google FLAN T5 and Base Sentiment Classifier recommended by TextRL library
2.ipynb -> Initial model with GPT2 and Base Sentiment Classifier recommended by TextRL library
3.ipynb -> Reward modifed to Min of 2 base sentiment classifiers
4.ipynb -> Dataset Modified to News Corpus
5.ipynb -> True model comparison strategy
6.ipynb -> Chabot Implementation using Facebook Blenderbot and Dialy Dialog dataset to achieve pessimistic responses.

To run these files, please perform the required installation for TextRL library. Also install Fuzzy Wuzzy and NLTK libraries for certain reward function calculations.

Run the ipynb directly to get the results. Please note, the used transformers are quite large in size and could use up significant amount of storage space.

P.S. Best models for Text generation is given in checkpoint and chatbot is given in bloom-test-3.

P.P.S. Link to the code and Models is as provided: 
https://iiitbac-my.sharepoint.com/:f:/g/personal/venkat_suprabath_iiitb_ac_in/EkfOfbUzVotJu9YowuIeNpQBVE6c7tx5xAYsh97VYslF9w?e=iiRnaA