# Thymio X Twitter

- [Summary](#summary)
- [Libraries](#libraries)
- [Installation](#installation)
- [Documentation](#documentation)
- [Credits](#credits)

## Summary 

[Thymio](https://www.thymio.org/) is an open-source educational robot designed by researchers from the [EPFL](https://www.epfl.ch/en/), in collaboration with [ECAL](https://www.ecal.ch/fr/100/homepage), and produced by Mobsya, a nonprofit association whose mission is to offer comprehensive, engaging STEAM journeys to learners of all ages.

This repository showcases a proof of concept I wrote for a [webinar about the Thymio robot](https://www.thymio.org/fr/webinar_post/)[^1] that connects to the Twitter API, fetches recent tweets where Thymio is mentioned, performs sentiment analysis on the content of the tweets, and activates the green Thymio leds if the result is positive, and the red leds if it's negative. Thus, it gives Thymio a kind of **artificial emotionnal intelligence**. 

Further developments would include improving the quality of my code, obviously, but also bringing the concept of creating a bridge between live feeds via API's and actual robots reacting to this live information. **Using Machine Learning on live feeds of information seems like an interesting path in giving connected objects a kind of autonomous and spontaneous intelligence**.

## Libraries

The main program uses the following libraries : 

- [TDM client](https://pypi.org/project/tdmclient/) : Communication with Thymio II robot via the Thymio Device Manager
- [Tweepy](https://www.tweepy.org/) : Python library for accessing the Twitter API
- [RE](https://docs.python.org/3/library/re.html) : Regular expressions operations
- [Textblob](https://textblob.readthedocs.io/en/dev/) : Python library for processing textual data

## Installation

- A comprehensive guide to using Thymio from scratch can be found here : https://www.thymio.org/products/programming-with-thymio-suite/. 
- In order to use the Twitter API, one has to create a developper account and request for API keys : https://developer.twitter.com/en/docs/twitter-api.
- A very useful guide to the process of creating a Twitter API developper account and setting up various twitter bots using Tweepy can be found here : https://realpython.com/twitter-bot-python-tweepy. 

## Documentation

Here is an html version of the slides I prepared for the actual [webinar about the Thymio robot](https://www.thymio.org/fr/webinar_post/) : https://github.com/elliotvaucher/thymio_twitter/blob/main/docs/presentation_thymio.html.

Note : this presentation was written in markdown via this tool : https://github.com/adamzap/landslide. 

The source markdown file is visible here, for information : https://github.com/elliotvaucher/thymio_twitter/blob/main/docs/thymio.md.

## Credits 

The functions for sentiment analysis using textblob were taken from this tutorial : https://www.geeksforgeeks.org/twitter-sentiment-analysis-using-python/. 
The step by step guide for setting-up Twitter API keys comes from here : https://realpython.com/twitter-bot-python-tweepy.

[^1]: The webinar presents a Python library used to control the robot with Python code. More information about controling Thymio with Python can be found [here](https://www.robot-advance.com/EN/actualite-python-with-thymio-complete-guide-228.htm). 
