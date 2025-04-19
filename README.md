# Multilingual AI Assistant with LLMOps Implementation

Welcome to the **Multilingual AI Assistant** project! This initiative focuses on developing a multilingual AI assistant powered by the Google Gemini (LLM) model API. By integrating with **Streamlit** for the UI and implementing **LLMOps** practices, we aim to create an efficient and scalable assistant for natural language interaction.

## Overview

The **Multilingual AI Assistant** project is designed to build an AI-powered assistant that can understand and respond to user queries in multiple languages. By leveraging the Google Gemini model API and using Streamlit for the UI, this project demonstrates LLMOps practices in developing and deploying conversational AI systems.

## Project Structure

The project is organized into the following key components:

- **Setup**: Provides scripts and instructions for setting up the project environment, including creating a virtual environment, installing dependencies, and configuring the project structure.

- **Development**: Contains the codebase for the AI assistant, including the main application script (`app.py`) and helper functions (`src/helper.py`).

- **API Integration**: Instructions for generating and configuring the Google Gemini API key to enable communication with the AI model.

- **Deployment**: Step-by-step guide for deploying the AI assistant to an AWS EC2 instance, ensuring accessibility and scalability.

## LLMOps Implementation Highlights

This project implements key LLMOps practices, including:

- **Environment Management**: A dedicated virtual environment (`multilingual`) is created to isolate project dependencies and ensure consistency across different setups.

- **Configuration Management**: Environment variables (stored in the `.env` file) are used to securely store sensitive information like API keys, ensuring safe and configurable deployments.

- **Infrastructure as Code**: The setup of AWS EC2 instances and environment configuration is automated via scripts, enabling reproducible and scalable deployments.

- **Continuous Deployment**: The project supports seamless deployment to AWS EC2 using Streamlit, enabling rapid iteration and easy updates.

## Usage

To get started with the project, follow these steps:

1. Set up your project environment by creating a virtual environment named `multilingual` and installing dependencies from the `requirements.txt` file.

2. Obtain a Google Gemini API key from the Google DeepMind website and set it as an environment variable in the `.env` file.

3. Run the Streamlit application locally with the command: `streamlit run app.py`. Interact with the assistant using voice and text inputs.

4. Deploy the AI assistant to an AWS EC2 instance following the provided deployment instructions, ensuring proper security groups and port mapping configurations.

5. Access the deployed assistant by connecting to the EC2 instance's public IP and interacting with the Streamlit app.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests related to LLMOps practices, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
