# Customized-LLM-APP
# TotalBodyTrainingCoach 🏋🏻‍♀️💪🏽

## Overview

TotalBodyTrainingCoach is an interactive chatbot application that provides expert guidance on anatomy, physiology, and exercise science. It combines the power of a large language model with a Retrieval-Augmented Generation (RAG) system to offer accurate and context-aware responses to user queries about physical training and body mechanics.

## Features

- **Intelligent Chatbot**: Utilizes the Zephyr-7b-beta model from HuggingFace for natural language interactions.
- **RAG System**: Implements a vector database for efficient retrieval of relevant information from a pre-loaded anatomy PDF.
- **User-Friendly Interface**: Built with Gradio for an easy-to-use chat interface.
- **Customizable Responses**: Configurable parameters for response generation, including temperature and top-p sampling.

## How It Works

1. **PDF Processing**: The application loads and processes an anatomy PDF, extracting text content from each page.
2. **Vector Database**: It builds a vector database using sentence embeddings of the extracted text.
3. **Query Processing**: When a user asks a question, the system searches for relevant information in the vector database.
4. **Response Generation**: The chatbot generates responses based on the user's query, retrieved relevant information, and a predefined system message that shapes its behavior as a DBT (Dialectical Behavior Therapy) coach.

## Usage

Users can interact with the chatbot by typing questions or selecting from predefined examples. The chatbot will provide informative responses about anatomy, physiology, and exercise-related topics.

## Setup and Running

(Include instructions for setting up and running the application, including any dependencies that need to be installed.)

## Disclaimer

The anatomy data used in this application is sourced from: https://www.mdthinducollege.org/ebooks/anatomy%20and%20Physiology/Functional_Anatomy.pdf

## Note

This application is designed for educational and informational purposes only. It should not be used as a substitute for professional medical advice, diagnosis, or treatment.
