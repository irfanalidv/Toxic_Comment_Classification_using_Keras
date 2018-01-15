# Toxic_Comment_Classification_using_Keras
Identify and classify toxic online comments

Discussing things you care about can be difficult. The threat of abuse and harassment online means that many people stop expressing themselves and give up on seeking different opinions. Platforms struggle to effectively facilitate conversations, leading many communities to limit or completely shut down user comments.

The [Conversation AI team](https://conversationai.github.io/), 

![conversation](https://user-images.githubusercontent.com/5808185/34948541-7bd8e3ec-fa33-11e7-9f3b-8ae8438f63e2.png)

a research initiative founded by [Jigsaw](https://jigsaw.google.com/) and Google (both a part of Alphabet) are working on tools to help improve online conversation. One area of focus is the study of negative online behaviors, like toxic comments (i.e. comments that are rude, disrespectful or otherwise likely to make someone leave a discussion). So far they’ve built a range of publicly available models served through the Perspective API, including toxicity. But the current models still make errors, and they don’t allow users to select which types of toxicity they’re interested in finding (e.g. some platforms may be fine with profanity, but not with other types of toxic content).

![per](https://user-images.githubusercontent.com/5808185/34948459-30e2a698-fa33-11e7-81ba-8fdc35722722.png)

https://perspectiveapi.com/#/

Here we will build a multi-headed model that’s capable of detecting different types of of toxicity like threats, obscenity, insults, and identity-based hate better than Perspective’s current models. You’ll be using a dataset of comments from Wikipedia’s talk page edits. Improvements to the current model will hopefully help online discussion become more productive and respectful.

Current Work @Google : https://github.com/conversationai/unintended-ml-bias-analysis

DataSet : https://github.com/conversationai/unintended-ml-bias-analysis/tree/master/data

GloVe: Global Vectors for Word Representation : https://nlp.stanford.edu/projects/glove/

![word](https://user-images.githubusercontent.com/5808185/34950497-54f7e830-fa39-11e7-9325-b6fb11705a97.png)
We will use these pre-trained embeddings when we need a way to quantify word co-occurrence (which also captures some aspects of word meaning.)

