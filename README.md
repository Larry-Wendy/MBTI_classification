# EECS-6893-final-project

- The Myers-Briggs Type Indicator (MBTI) is an introspective self-report questionnaire that indicates different psychological preferences in how people perceive the world and make decisions. Knowing MBTI can help users understand themselves and adjust the life and work according to their own personality tendencies.  
- This project provide a simple system to make predictions of Twitter user’s MBTI personality. The input of the system is user’s twitter name, and the system should return MBTI personality type predicted based on the user's tweets.
Compared to the traditional way of filling out questionnaires, we using social platform data to train classification model and make prediction. We also build a user-friendly web application which let users get their personality type result faster and easier.


[![demo](https://github.com/Larry-Wendy/MBTI_classification/blob/main/coverpage.png)](https://youtu.be/aFgrYO8kDU4 "demo")

__Dataset__:  
This is a dataset that contains 106K records of preprocessed posts online from the PersonalityCafe forum and Reddit. Where each post is 500 words long and has been annotated with personality type. The dataset was covered by Dylan Storey and Mitchell Jolly. The dataset has a volume of 346MB. The velocity of the dataset is 0 since it stopped updating. There are a total of 16 personalities included. The original dataset has an unbalanced distribution of personality. Therefore, we have used an oversample to balance the dataset and made each personality have 25K entries.
