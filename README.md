# Assistive-Chatbot-for-Academic-Information
Academia chatbot is a web-enabled chatbot powered by Google’s Dialogflow, will can be used to help the students at MITWPU to easily fetch details about their respective subjects, its course pattern, marks distribution etc.

# Platform: Google’s Dialogflow
• It is an End-to-end, Build-once Deploy-everywhere Development Suite. We can build voice or text-based conversational interfaces for almost all types of devices and websites and mobile apps and messaging platforms like facebook, slack, telegram etc
• Chatbot using dialogflow enables natural and rich interactions between the user and our business. The input can be in the text format or it can be a voice input.

Agent
As a part of building a chatbot, we preprocess the data to create topics and then extract and save the associated synonyms for given topics. This data is uploaded to the Dialogflow agent.
The agent is like a virtual agent or a bot that handles the conversation with the end users.

Entity:
The preprocessed data is uploaded to the agent and the topics are uploaded in entities. Entities are dialogflow’s mechanism for identifying and extracting useful data from natural language inputs. They pick out specific pieces of information that the users mention.

Intent
Intents map the user input to the responses. In each intent we define the examples of user statements that can trigger the intent, what to extract from the statement and how to respond.

Response:
The response is what is spoken or written back to the user.
Dialogflow allows us to use different types of responses like text, cards, images, audio.
