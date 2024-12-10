# Parenting Chatbot Project

Welcome to the Parenting Chatbot Project! This chatbot is designed to provide accurate, readable, and accessible parenting advice for parents of newborns up to children one year old. Leveraging advanced language learning models (LLMs), this system pulls information from credible sources to assist parents effectively.

## Project Overview

The Parenting Chatbot aims to streamline scattered and often unreliable parenting information into a centralized, reliable source. Utilizing data from reputable organizations such as the CDC and Just in Time Parenting, this chatbot helps new parents navigate the complexities of early parenthood with confidence.

## System Architecture

- **Data Sources**: Sourced from reputable organizations, ensuring reliability and trustworthiness.
- **LLM Support**: Powered by the Gemini 1.5 Flash 001 model, this setup tests the capabilities of free AI models in delivering high-quality content.
- **Database Segmentation**: Organized into four specific categories: child development, child care, health and well-being, and food and nutrition.
- **Query Handling**: Incorporates a question classifier to route queries to the appropriate content-specific agent.

## Features

- **Age-Specific Solutions**: Delivers relevant and practical advice across different developmental stages.
- **Accessibility**: Crafted to be easily understandable, accommodating all reading levels.
- **User Interface**: Designed for straightforward interactions to ensure ease of use.

## Installation

To get started with the Parenting Chatbot, clone this repository and set up the environment:

```bash
git clone https://github.com/yourusername/parenting-chatbot-project.git
cd parenting-chatbot-project
pip install -r requirements.txt
python chatbot.py

