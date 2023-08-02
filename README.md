# Maverick <br> 
This repository contains the paper presenting the algorithm Maverick that I developed in my internship as a Machine Learning Engineer at Vela Partners.
The model is published on the AI community [Hugging Face](https://huggingface.co/lukasec/Maverick).

**Abstract** <br>
Maverick (MAV) is an AI-enabled algorithm to guide Venture Capital investment by leveraging BERT - the state-of-the-art deep learning model for NLP. Its ultimate goal is to predict the success of early-stage start-ups.

In Venture Capital (VC) there are two types of successful start-ups: those that replace existing incumbents (type 1), and those that create new markets (type 2). In order to predict the success of a start-up with respect to both types, Maverick consists of two models:
* **MAV-Moneyball** predicts success of early stage start-ups of type 1.
* **MAV-Midas**  predicts whether a start-up fits current investment trends made by the most successful brand and long-tail investors, thereby taking into account new emerging markets that do not necessarily already have established successful start-ups leading them - ie. start-ups of type 2.<br><br>

Maverick is developed through a transfer learning approach, by fine-tuning a pre-trained BERT model for type 1 and type 2 classification. In this paper we present Maverick, its development, and its performance. Notably, both MAV-Moneyball and MAV-Midas achieve a true positive ratio greater than 70%, which in the context of VC investment is one of the most important evaluation criteria - it is the percentage of successful companies predicted to be successful by Maverick.

If you wish to request access to the repository containing the code used to train and develop Maverick send me an email at [Luka Secilmis](mailto:lukasecilmis@gmail.com?subject=[GitHub]%20Access%20to%20MAV%20code).
