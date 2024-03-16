# My_events_chatbot
This is an event organization chatbot

## Technologies Uses
  1. Python
  2. Tensorflow
  3. MySQL
  4. socketio 
  5. SpacyNLP
  6. Rasa NLP
## Core functionalities
  1. Help organize events
  2. Recommends events from the internet and those that have been organized by organizers using the chatbot
  3. Generate tickets for an event
  4. All users to advertise their merchandise
  5. Recommend merchandise to event organizers
## Getting started 
1. Install anaconda
2. Install rasa in a Python Anaconda virtual environment. Follow the link https://www.youtube.com/watch?v=GlR60CvTh8A
3. Install the modules in the actions.py file
4. open two terminals in your virtual environment where rasa is installed
5. In the first one, run rasa run actions
6. In the second one, run rasa run -m models --enable-api --cors "*"
7. Open localhost using http://localhost:5005
