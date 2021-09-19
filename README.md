# Ad Campaign Performance: A/B Hypothesis Testing

## Introduction

SmartAd is a mobile first advertiser agency that designs intuitive touch-enabled advertising. It provides brands with an automated advertising experience via machine learning and creative excellence. Their company is based on the principle of voluntary participation which is proven to increase brand engagement and memorability 10 x more than static alternatives.

## Project Overview

In this case, the company runs an online ad for a client with the intention of increasing brand awareness and would like to know the performance of the advert and determine whether users are engaging with it or not. To do this easily, SmartAd provides an additional service called Brand Impact Optimiser (BIO), a lightweight questionnaire, served with every campaign to determine the impact of the creative ad they design, on a various upper funnel metrics, including memorability and brand sentiment. The task (and this is what this work explores) is to design a reliable hypothesis testing algorithm for the BIO service and determine whether a recent advertising campaign resulted in a significant lift in brand awareness. The goal of the analysis done here is to test if the ads that SmartAd runs resulted in a significant lift in brand awareness. 


## Data Description

The BIO data for this project is a “Yes” and “No” response of online users to the following question

Q: Do you know the brand Lux?
		O  Yes
		O  No

This is a test run and the main objective is to validate the hypothesis algorithm you built. SmartAd ran this campaign from 3-10 July 2020. The users that were presented with the questionnaire above were chosen according to the following rule:

Control: users who have been shown a dummy ad
Exposed: users who have been shown a creative (ad) that was designed by SmartAd for the client. 

