# Chatbot_Rasa

![Chatbot_Rasa](https://img.shields.io/badge/Chatbot_Rasa-Ready-brightgreen.svg)

Welcome to Chatbot_Rasa! This project is a demonstration of a chatbot built using Rasa, a powerful open-source framework for building conversational AI. With Rasa, you can create intelligent chatbots and virtual assistants that can handle complex conversations. 

In this one we focus on the domain of Real-Estate, where the bot has the capabilities to schedule appointment, solve FAQs, etc.

## Overview

### Features

- **Natural Language Understanding**: Chatbot_Rasa utilizes Rasa's NLU to understand and extract intents and entities from user messages.
- **Interactive Chat Interface**: Engage in conversations with the chatbot through the command line interface or integrate it into your own applications.
- **Customizable Actions**: You can define custom actions and responses for the chatbot to perform, making it highly adaptable to your specific use cases.
- **Training and Fine-tuning**: Train the chatbot using your own dataset or fine-tune pre-trained models to suit your domain.
- **Integration Ready**: Easily integrate this chatbot into web applications, messaging platforms, and more.

### Prerequisites

Before you start, make sure you have the following installed:

- [Python](https://www.python.org/downloads/) (>=3.6)
- [Rasa](https://rasa.com/docs/rasa/installation) (>=2.0)
- [spaCy](https://spacy.io/usage) (for NLU)

### Getting Started

1. Clone this repository:

   ```shell
   git clone https://github.com/nikhilm21/Chatbot_Rasa.git

2. Navigate to the project directory
   ```shell
   cd Chatbot_Rasa


3. Run the action server
   ```shell
   rasa run actions
   docker run -p 8000:8000 rasa/duckling
   rasa x

4. Run the action server
  
  ```shell
  rasa run actions
  docker run -p 8000:8000 rasa/duckling
  rasa x
  ```

### Interact with the chatbot: 
You can interact with the chatbot by sending POST requests to http://localhost:5005/webhooks/rest/webhook. You can also use the Rasa X interface for more interactive conversation management. 

### Customization
To customize the chatbot for your specific use case, you can modify the training data and fine-tune the models located in the data directory. Add your own intents, responses, and actions to tailor the chatbot to your requirements.

### License
This project is licensed under the MIT License. For more details, see the LICENSE file.

### Acknowledgments
- Rasa: The chatbot framework used in this project.
- spaCy: Used for natural language understanding.




   
