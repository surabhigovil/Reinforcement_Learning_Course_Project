# Sequence to Sequence Chatbot with Policy Gradient 

We would like to appreciate this superb beginner tutorial on chatbot by PyTorch https://pytorch.org/tutorials/beginner/chatbot_tutorial.html for providing us with the base attention based sequence to sequence model. The creators of https://github.com/VidhushiniSrinivasan16/EmotionalNLG for the reward functions.

A policy trained to act based on observations is policy gradient. How this works is by initializing the RL system with a general response policy learnt from our seq2seq model, which is then tuned using the policy gradient method. We utilized the <a href="http://yanran.li/dailydialog">DailyDialog: A Manually Labelled Multi-turn Dialogue Dataset</a> that consists of dialogues which reflect our daily communication style and cover various topics about day to day life

The attention mechanism used in Loung as we can see significant advantage over Bahdanau. 
![image](https://user-images.githubusercontent.com/10840984/144695376-aa3b3a1b-ffc7-4161-9361-dde143e0b38e.png)

The Bahdanau Architecture (Left) vs. the Luong Architecture (Right). Taken from [“Advanced Deep Learning with Python“] (https://www.amazon.com/Advanced-Deep-Learning-Python-next-generation/dp/178995617X)

## Rewards:
Ease of answering, Information flow and Semantic Coherence

# Results  

# Demo
![image](https://user-images.githubusercontent.com/10840984/144695651-39ec2d3b-578a-43e2-b4d1-71395884b843.png)
