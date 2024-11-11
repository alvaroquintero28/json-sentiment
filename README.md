# P4: Employ Requests, JSON, NLP with SpaCy

## Project Overview

Use a Working API and Working With Web Information

## Objectives

This exercise illustrates how to access web-hosted APIs, get back a response in JSONLinks to an external site. format, and extract the information we need from the JSON. Accessing APIs is a key skill for data analysts. We can use web APIs to get stock data, weather data, and much more. We'll use an API to access song lyrics or poems in this exercise. We don't care which API - there are many and they change. The skill skills are being able to (a) make an API request and (b) find the information we need in the returned response. 

## Songs in this project

-'Baby' by Justin Bieber
-'Back At One' by Brian McKnight 
-'Promises' by Maverick City Music 
-'Umbrella' by Rihanna


## Tools and Libraries

- lyrics.ovh API: For accessing lyrics data.

- spaCy: For natural language processing.

- SpacyTextBlob: For sentiment analysis.

## Dependencies Installed

- **spaCy**
- **SpacyTextBlob**
- **en_core_web_sm model for spaCy**

To install these dependencies, use the following commands:

```bash
python -m venv .env
source .env/bin/activate
pip install -U pip setuptools wheel
pip install -U spacy
python -m spacy download en_core_web_sm
