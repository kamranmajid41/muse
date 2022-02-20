![alt text](https://github.com/kamranmajid41/muse/blob/main/muse.png)
## Generate AI Rap Lyrics Using Your Favorite Artist and Title

### Installation
```sh
# clone the repo
git clone https://github.com/kamranmajid41/muse

# install requirements
pip install -r requirements.txt
```

### Running the Web-App Locally

```sh
# navigate to the muse folder 
cd muse

# run app.py
python3 app.py

# check out http://0.0.0.0:8080
```
## Inspiration 

We were inspired by the major breakthroughs in using AI to create music. Wanting to do something along these lines, we decided to make Muse - an RNN and user-powered lyrics generator. 

## What it does
Muse takes user input and uses a trained RNN model to generate lyrics that are relevant to the given topic in a familiar rapper style. 

## How we built it 
We built Muse using various technologies for different parts. For the Recurrent Neural Network, we used tensorflow and keras primarily, and used the external GPU in Google Colab. We built the backend using Flask, and the frontend in Bootstrap using CSS and JS. 

## Challenges we ran into and what we learned 
Our initial plan was to use Google App Engine to develop and host our web application. However, the steep learning curve made it difficult to do so, and, despite learning a lot about Google App Engine, we ended up not having the time to use it. 

## Accomplishments that we’re proud of 
We’re really proud that we were able to complete a polished, functional project in such a short time period. Also, our RNN achieved state-of-the-art metrics. 

## What’s next for Muse
In the future, we would like to make Muse span a larger dataset and take in more user input, including emotion, length, and even specific artists. Also, we would like to use Google App Engine to develop and host our web application. 
