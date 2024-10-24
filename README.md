## Conversational AI Agents with GPT-3.5, DALL-E, and Code Execution
This project demonstrates the creation and configuration of conversational AI agents using GPT-3.5 for natural language interactions, DALL-E for image generation, and a local command-line executor for code execution automation. The multi-agent system can simulate interactions in various contexts, such as comedy shows, while integrating advanced automation capabilities.

## Features
- Conversational Agents: Configured agents using OpenAI's GPT-3.5 for generating human-like text responses. The agents are designed with specific personalities and goals, such as a comedian delivering jokes and an audience providing feedback.

- Multi-Agent Interaction: Created a dialogue system where multiple agents interact with each other, each assigned specific roles. For example, the "Comedian" agent delivers jokes while the "Audience" agent reacts, with interactions being limited by custom auto-reply configurations.

- DALL-E Image Generation: Integrated OpenAI’s DALL-E model to generate images from text descriptions provided by the agents or user input. This functionality allows for automatic image generation in conversation flows.

- Code Execution Automation: Implemented an agent capable of executing Python code snippets locally. The agent processes the code, runs it in a controlled environment, and returns the results or outputs (e.g., plots, data analysis). A sample block generates a line plot using pandas and matplotlib.

- Image Extraction from Conversations: Automated extraction of images generated or referenced in the conversation, allowing for easy display or further processing of visual content exchanged between agents.

- API Integration: Managed API keys and configurations through the userdata object, allowing seamless interaction with OpenAI services for language modeling and image generation.

## Technologies Used
- Python
- OpenAI API:
- GPT-3.5 (for text-based interactions)
- DALL-E (for image generation)
- pyautogen (for managing agent behavior)
- Google Colab (for handling API keys and environment configuration)
- pandas, numpy, matplotlib (for code execution examples)
