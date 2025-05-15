# NewsLDA

## Description

Inspired by the recently published JF paper 'Business News and Business Cycles' by Leland Bybee, Bryan Kelly, Asaf Menla, and Dacheng Xiu, this project aims at identifying central topics from news stories that have predictive power over future commodity market developments. 

I do, unfortunately, not have access to the Wall Street Journal (WSJ) dataset used in the paper, but the commodity-related news stories of Platts should also work for this purpose. While WSJ covers both economic and non-economic news, Platts focuses solely on information relevant to commodity markets – exactly where my interest is in.

In a deviation from the original methodology, I employ BERTopic, which is based on Transformer embeddings and is considered a state-of-the-art method in topic modeling. The original paper uses Latent Dirichlet Allocation (LDA), which appears to work reasonably well, but is methodologically outdated.

As the authors point out, news text is a mirror of the prevailing economic issues that are important to both news consumers and producers. Similarly, Platts news should reflect the state of commodity markets and the topics market participants are concerned with. 

Are recurring patterns in the news that explain commodity market regimes? 
Let's find out.

