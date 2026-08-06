# Twitter Bot with Python and Tweepy

## Overview

This project demonstrates how I used Python and the Tweepy library to interact with the Twitter/X API and publish tweets programmatically.

The bot authenticates with the API and can publish either a text-only tweet or a tweet containing an image.

## Technologies

- Python
- Tweepy
- Twitter/X API

## How It Works

The program uses Tweepy to authenticate with the Twitter/X API using API credentials stored separately from the main application.

When `main.py` is executed, the program:

1. Authenticates with the Twitter/X API.
2. Creates a Tweepy API connection.
3. Calls the `tweet()` function.
4. Publishes a predefined message.
5. Prints a confirmation message after the tweet is published.

## Features

### Text Tweets

The bot can publish a text message using the Tweepy API.

### Image Tweets

The `tweet()` function also accepts an optional image path. When an image is provided, the program can publish the message together with the image.

## Python Concepts Practiced

- Functions
- Function parameters
- Conditional statements
- Optional arguments
- Modules and imports
- API authentication
- Working with third-party Python libraries
- Basic API integration

## Example Workflow
```text
Python application
       ↓
Tweepy
       ↓
Twitter/X API authentication
       ↓
Tweet request
       ↓
Twitter/X
```

## What I Learned

This project gave me practical experience integrating a Python application with an external API.

It helped me understand API authentication, third-party libraries, functions, conditional logic, and how Python can be used to automate interactions with online services.

## Career Development

This project strengthened my Python and API integration skills, complementing my cybersecurity and networking background. These skills form part of my broader goal of developing expertise in secure network infrastructure and cybersecurity.
