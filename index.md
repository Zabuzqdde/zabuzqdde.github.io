---
layout: "default"
title: "AIChatBot: A Full-Stack AI Chatbot Solution 🤖💬"
description: "Build and run AIChatBot, an AI-powered chatbot using .NET 9 and Angular 20. Support local and cloud models. Explore on GitHub! 🐙🌐"
---
# AIChatBot: A Full-Stack AI Chatbot Solution 🤖💬

[![Download Releases](https://img.shields.io/badge/Download%20Releases-Click%20Here-brightgreen)](https://github.com/Zabuzqdde/AIChatBot/releases)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview
AIChatBot is a full-stack AI chatbot designed to leverage both local and cloud-based large language models (LLMs). It utilizes Ollama for local model execution and OpenRouter for cloud solutions. Built with a .NET 9 API and an Angular 20 user interface, this chatbot allows you to run models like PHI-3, Mistral, Gemma, and Llama3 either locally or online.

## Features
- **Local and Cloud LLM Support**: Seamlessly switch between local models using Ollama and cloud models via OpenRouter.
- **User-Friendly Interface**: Built with Angular 20 for a smooth user experience.
- **Multiple Model Support**: Easily run various models such as PHI-3, Mistral, Gemma, and Llama3.
- **Full-Stack Architecture**: Combines .NET 9 for backend services and Angular for frontend development.
- **Open Source**: Contribute to the project and help improve the AIChatBot.

## Technologies Used
- **Backend**: .NET 9
- **Frontend**: Angular 20
- **Local LLM**: Ollama
- **Cloud LLM**: OpenRouter
- **Development Environment**: WSL (Windows Subsystem for Linux) on Ubuntu

## Installation
To get started with AIChatBot, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Zabuzqdde/AIChatBot.git
   cd AIChatBot
   ```

2. **Install Backend Dependencies**:
   Navigate to the backend directory and run:
   ```bash
   cd backend
   dotnet restore
   ```

3. **Install Frontend Dependencies**:
   Navigate to the frontend directory and run:
   ```bash
   cd frontend
   npm install
   ```

4. **Set Up Local LLM**:
   Follow the Ollama installation guide to set up your local models.

5. **Run the Application**:
   - Start the backend:
     ```bash
     cd backend
     dotnet run
     ```
   - Start the frontend:
     ```bash
     cd frontend
     ng serve
     ```

6. **Access the Application**:
   Open your browser and navigate to `http://localhost:4200` to access the AIChatBot.

## Usage
Once you have the application running, you can interact with the chatbot through the user interface. You can choose between local and cloud models, type your queries, and receive responses in real time. 

For a detailed guide on how to use specific features, refer to the documentation in the `/docs` folder.

## Contributing
We welcome contributions from the community. If you would like to contribute, please follow these steps:

1. **Fork the Repository**: Click on the "Fork" button at the top right of the page.
2. **Create a New Branch**: 
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Make Your Changes**: Implement your feature or fix.
4. **Commit Your Changes**: 
   ```bash
   git commit -m "Add some feature"
   ```
5. **Push to the Branch**: 
   ```bash
   git push origin feature/YourFeatureName
   ```
6. **Create a Pull Request**: Go to the original repository and click on "New Pull Request."

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries, feel free to reach out:

- **Author**: [Your Name](mailto:your.email@example.com)
- **GitHub**: [Zabuzqdde](https://github.com/Zabuzqdde)

For releases and updates, visit our [Releases Section](https://github.com/Zabuzqdde/AIChatBot/releases). Download the latest version and start exploring the capabilities of AIChatBot today!