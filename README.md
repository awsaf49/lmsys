# LMSYS - Chatbot Arena Human Preference Predictions with [KerasNLP](https://github.com/keras-team/keras-nlp) and [Keras](https://github.com/keras-team/keras)

<div align="center">
    <img src="https://i.ibb.co/wJMF5HL/lmsys.png">
</div>

In this competition, our aim is to predict which LLM responses users will prefer in a head-to-head battle between chatbots powered by large language models (LLMs). In other words, the goal of the competition is to predict the preferences of the judges and determine the likelihood that a given prompt/response pair is selected as the winner. This notebook will guide you through the process of fine-tuning the **DebertaV3** model for this competition using the **Shared Weight** strategy with KerasNLP. This strategy is similar to how Multiple Choice Question (MCQ) models are trained. Additionally, we will use mixed precision for faster training and inference.

> **Note**: You can access the notebook from [**Kaggle**](https://www.kaggle.com/code/awsaf49/lmsys-kerasnlp-starter/) or here in the `/notebooks` folder.
