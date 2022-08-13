# FreshOrStaleFruits-ImageClassification




Image classification was done through **Create ML**, an XCode Developer Tool. The trained ML can be found within the repository under the name "FreshOrRottenFruitBetter.mlmodel" in the folder called SmartCameraLBTA.

Dataset of various different stale and fresh fruits images was found on **Kaggle** by Adithya Shirvastava, Rahul Sohadani, and Naren Khatwani.



----
FROM DEVPOST SUBMISSION

## Inspiration
Ever wonder if the fruit you're eating is safe to eat? According to CDC, each year 48 million people get sick from a foodborne illness." ([link](https://www.cdc.gov/foodsafety/foodborne-germs.html#:~:text=CDC%20estimates%20that%20each%20year,are%20hospitalized%2C%20and%203%2C000%20die.) When fruits get spoiled they can be contaminated with various pathogens such as bacteria and molds, along with others. "Like most foods, fruits can go bad and become harmful to your health" ([link] (https://www.livestrong.com/article/473318-how-to-tell-if-a-fruit-is-spoiled/). In order to ensure the safety of the fruits and vegetables we eat daily, I decided to make an artificial intelligence program that separates stale fruits from fresh fruits.


## Real-life application

This software can be used in supermarkets when they receive produce from farms to make sure that the given fruits are fresh. This saves manpower by allowing the AI software to identify stale fruits (allowing for them to be put away).

## What it does
Using tens of thousands of carefully selected images of fresh and stale fruits from a database, artificial intelligence is able to accurately identify whether a given fruit is safe to eat. All the user has to do is to point their phone's back camera at the concerning area, and the app will output a description along with a confidence rating.

## How I built it

I consulted a University student and the person referred me to the possibility of building an AI model through Xcode. Upon my own investigation, I learned that Xcode provides a free developer tool for building AI models. So, I took the opportunity to build my own Machine Learning Model (MLModel). On Kaggle, a site that a conveniently discovered, I found multiple datasets of thousands of images of stale and fresh fruits. With that, I went to Youtube to find some guidance on how to code a real-time back camera in the app (Brian Voong's video).  Finally, I assembled the ML Model and was able to integrate it into my app through the code that I wrote on Xcode.

## Challenges I ran into

Initially, it was difficult to find an appropriate way to create an artificial intelligence model, and I indulged in a lot of Google Searches that ultimately lead me astray. In addition, later on in the project, I had many difficulties with putting a back camera on the app.  

## Accomplishments that I'm proud of

I am proud of the fact that I was able to successfully make a machine learning app that correctly identifies the given fruit, seeing as was my first time with any sort of machine learning environment.

## What we learned

I learned how accessible it is to build an ML Model and integrate it into any code.

## What's next for SkinDoc

In order to make SkinDoc as accurate as possible, I would need to aggregate more images of the given conditions in the dataset. The more images that are in the dataset result in a more accurate report and a higher confidence rating. Furthermore, I would make a five-second stopping point for the imaging and have a screen pop up with the mean result that appeared after the camera sees the given fruit.
