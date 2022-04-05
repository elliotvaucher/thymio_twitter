# Thymio X Twitter

**Pitch : Using Twitter + NLP to give Thymio artificial (emotional) intelligence.**

- [Summary](#summary)
- [Libraries](#libraries)
- [Installation](#installation)

## Summary 

[Thymio](https://www.thymio.org/) is an open-source educational robot designed by researchers from the [EPFL](https://www.epfl.ch/en/), in collaboration with [ECAL](https://www.ecal.ch/fr/100/homepage), and produced by Mobsya, a nonprofit association whose mission is to offer comprehensive, engaging STEAM journeys to learners of all ages.

This repository showcases a proof of concept I wrote for a [webinar about the Thymio robot](https://www.thymio.org/fr/webinar_post/). The webinar presents a Python library used to control the robot with Python code. More information about controling Thymio with Python can be found [here](https://www.robot-advance.com/EN/actualite-python-with-thymio-complete-guide-228.htm). 

## Libraries

The main program uses the following libraries : 

- [TDM client](https://pypi.org/project/tdmclient/) : Communication with Thymio II robot via the Thymio Device Manager
- [Tweepy](https://www.tweepy.org/) : Python library for accessing the Twitter API
- [RE](https://docs.python.org/3/library/re.html) : Regular expressions operations
- [Textblob](https://textblob.readthedocs.io/en/dev/) : Python (2 and 3) library for processing textual data

## Installation

- A comprehensive guide to using Thymio from scratch can be found here : https://www.thymio.org/products/programming-with-thymio-suite/. 
- In order to use the Twitter API, one has to create a developper account and request for API keys : https://developer.twitter.com/en/docs/twitter-api.
- A very useful guide to the process of creating a Twitter API developper account and setting up various twitter bots using Tweepy can be found here : https://realpython.com/twitter-bot-python-tweepy. 
