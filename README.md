# South Indian Aunty Chef: Food Recommendation Agent

## Overview

This project demonstrates the integration of Autogen with Langchain to create a food recommendation system using a HuggingFace language model. The system simulates a South Indian aunty chef who provides recipe recommendations and cooking instructions in a friendly, colloquial manner.

The project showcases the compatibility of Langchain with Autogen, opening up possibilities for using various Language Models (LLMs) within the Autogen framework. It serves as both a demonstration of this integration and a fun, interactive food recommendation system.

Related Blog [Post](https://medium.com/@techwithkrooz/cooking-up-ai-building-a-south-indian-aunty-chef-with-autogen-and-langchain-26163dd4eaa3)
## Features

- Custom model client for loading and using HuggingFace models with Autogen
- Integration of Langchain with Autogen for expanded LLM compatibility
- Conversational AI agents: a South Indian Aunty Chef and a Foodie user
- Recipe recommendations based on user preferences
- Step-by-step cooking instructions with time estimates
- Culturally flavored interactions with South Indian English slang

## Setup

1. Clone the repository:
2. Navigate to the project directory:
```python
cd FoodRec-Agent
```
3. Install the required dependencies:
```python
pip install -r requirements.txt
```

## Usage

1. Open the `application.ipynb` notebook in Jupyter or your preferred environment.

2. Run the cells in order to set up the custom model client, configure the agents, and start the conversation.

3. Interact with the South Indian Aunty Chef by expressing your food preferences or asking for recipe recommendations.

## How It Works

1. The project uses a custom `CustomModelClient` to load and interact with the HuggingFace model (Phi-3.5-mini-instruct).

2. Two Autogen agents are created:
- `Chef`: The South Indian Aunty who provides recipes and cooking advice
- `Foodie`: The user agent that interacts with the Chef

3. The conversation is initiated, allowing the user to request recipes or cooking tips.

4. The Chef agent responds with recipe suggestions, ingredients, preparation steps, and cooking times, all in a friendly South Indian English style.

## Future Directions

1. **RAG System Implementation**: 
- Integrate a Retrieval-Augmented Generation (RAG) system to enhance recipe recommendations.
- Create a database of stored recipes that the LLM can retrieve and reason from.
- Implement vector search for efficient recipe retrieval based on user preferences.

2. **Multi-modal Interactions**:
- Add support for image input/output to show and recognize ingredients or dishes.
- Implement voice interaction for a more natural cooking assistant experience.

3. **Personalization**:
- Develop a user profile system to remember preferences and dietary restrictions.
- Implement a learning mechanism to improve recommendations over time.


## Contributing

Contributions to improve the South Indian Aunty Chef project are welcome! Please feel free to submit pull requests or open issues for bugs and feature requests.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Autogen library for providing the conversational AI framework
- Langchain for enabling easy integration with various LLMs
- HuggingFace for the Phi-3.5-mini-instruct model
- Claude 3.5 Sonnet for helping me to correct the grammer and code
