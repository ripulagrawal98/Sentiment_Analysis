# Sentiment_Analysis_for_drugs
The <b>training dataset</b> contains reviews for 102 different drugs along with their sentiments as <b>positive, negative, neutral</b>.<br>
The language used in this is not grammatically correct as some uses sarcasm and expresses their sentiments w.r.t. each drug.
One thing is like one review can have different sentiment for different drugs respectively.<br> So to make predictions for sentiments on unseen data I've used <b>NLP (Natural Language Processing)</b> based technique i.e. <b>Bag of Words</b> to make features and also applied the name of drugs respect to each review.<br>
As it has three classes to predict so it becomes multi-classification so for an algorithm I've used <b>Support Vector Classifier</b>.
<br>In the end, to measure how relevant how our model is we've measure F1 score.
