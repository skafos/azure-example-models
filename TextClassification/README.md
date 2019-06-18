# Text Classification
<a href="https://notebooks.azure.com/Skafos/projects/text-classification-examples">    <img src="https://notebooks.azure.com/launch.svg" /></a>

Text classification is the task of assigning a label to some bit of text. Here
 we start you off with a basic example:

- **Sentiment Classifier**:
  Trains a model to classify user text as positive (5), negative (1), or in between.
- **Spam or Ham**:
 Trains a model to classify user text as "spam" (bad) or "ham" (good).
- **Topic Classifier**:
 Trains a model to classify user text into one of 20 different topics.

## Tips and "Gotchas"
 -  **Azure Notebooks**: While Notebooks are in `Preview` mode (beta), some features might be buggy or not available. If you are having trouble with dependencies in your JLab environment. Try waiting a few minutes, restarting the Python 3.6 kernel, and trying again.
 -  **Common Text Classification Tasks**:
   - ***Sentiment Classification***: How positive or negative is a piece of text? Typically trained with text data
     representing user reviews and respective ratings on a scale 1-5. The starter model in this repo contains a basic sentiment classifier trained on yelp reviews.
   - ***Spam Classification***: How likely is it that a piece of text is considered "spam" or "ham"? Typically trained with
    text data paired with the appropriate label (spam or ham). The starter model in this repo contains a basic spam classifier trained on SMS text message data.
   - ***Topic Identification***: What is the topic or subject matter of a piece of text? Typically trained with text
    data paired with related categories. The starter model in this repo contains a basic topic classifier trained on news articles labeled with corresponding category (provided by scikit-learn package).
 - **Wrangling Text w/ Turi Create**: Text comes in a host of different formats. Fortunately, the Turi Create text classifier handles all [tokenization](https://nlp.stanford.edu/IR-book/html/htmledition/tokenization-1.html), and text feature engineering, and cleaning of your text data automatically.

## Need Help?
Didn't find something you need? Confused by something? Need more guidance?

- [**Check out our platform documentation**](https://docs.skafos.ai)

Please contact us with questions or feedback! Here are two ways:

-  [**Signup for our Slack Channel**](https://join.slack.com/t/metismachine-skafos/shared_invite/enQtNTAxMzEwOTk2NzA5LThjMmMyY2JkNTkwNDQ1YjgyYjFiY2MyMjRkMzYyM2E4MjUxNTJmYmQyODVhZWM2MjQwMjE5ZGM1Y2YwN2M5ODI)
-  [**Find us on Reddit**](https://reddit.com/r/skafos)

Also checkout Turi Create's [**documentation**](https://apple.github.io/turicreate/docs/userguide/text_classifier/) on
 text classification basics.
