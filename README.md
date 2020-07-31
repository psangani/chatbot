
# Mitr - Chatbot solution that can help people cope with a pandemic like COVID-19

![alt text](https://github.com/psangani/chatbot/blob/master/ProfilePic.png)

'Mitr'(companion in Hindi) is a chatbot that can help people cope up with the mental issues arising due to pandemic like Covid-19.    

# Problem Statement -

- Humans as are social creatures and need social interaction with others to flourish. Socializing is our basic behavior and from the beginning we are taught to excel in it. 
- But, current pandemic situation has changed this notion completely. The best way to avoid contracting Covid-19 is physical distancing, self-quarantine, isolating oneself from the world. Since past few months whole world has adopted some level of isolation and this will be the new norm for few more months at least
- Individuals set in self quarantine, isolation may experience wide scope of emotions, fear, anger, stress. And this prolonged isolation and problems can lead to mental health and anxiety.
- Depression is a very serious problem and because of this pandemic, there is a risk of a steep increase in the number of patients. 

# Our Solution - 

- ‘Mitr’ (companion in Hindi), a Chat-bot will be a smart tool for the users who can interact with it on Web or install on smartphones. 
- The bot will ask few basic questions to understand users mental well-being, emotions and gets the GPS location upon users consent. Based on these questions, Mitr will analyze and recommend tailored self-care, positive activities.
- Application leverages IBM Watson Assistant API for NLP, machine learning to make smart decisions. It also uses Google Map API to get user's location after user gives consent.\
- For the decision-making intents, entities, dialogs and dialog flow have been created. Application seeks users location and for the therapist name/address, app calls Google map API and integrates with Webhooks.
- Currently the application is integrated with Slack. 

## Architecture Diagram - 

![alt text](https://github.com/psangani/chatbot/blob/master/architecture%20diagram.PNG)


# Planned Improvements - 

- The bot can be developed as a standalone Android/iOS application or a website that anyone can use. 
- This will help the bot to serve more users since the users would not need to install slack and integrate the bot onto the slack channel to start interacting with the bot. 
- The website or the app can have this bot as a first step to gauge the mental health of the user and then based on that the app can show relevant information to the user. 
- The information can be anything ranging from motivational videos, books to engaging and interesting hobbies that the user can pursue to reduce stress.
- The app can also have therapist and 24x7 support persons to talk to the users.

# License - 
GPL-3.0 License 
