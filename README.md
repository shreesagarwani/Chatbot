# Chatbot
Creatiing a simple charbot
There are broadly two variants of chatbots, Rule-based and Self-learning.

A rule-based bot uses some rules on which it is trained, while a self-learning bot uses some machine-learning-based approach to chat.

We will show you how to create a simple and quick chatbot in python using a rule-based approach.

#Lets Import the libraries
from nltk.chat.util import Chat, reflections

Create the chatbots list of recognizable patterns and it’s a response to those patterns. To do this we will create a variable called pairs.

After finishing the patterns and responses, let’s take a look at something called reflections. Reflections is a dictionary file that contains a set of input values and corresponding output values.

For example, if the string input was “I am a programmer”, then the output would be “you are a programmer”.
