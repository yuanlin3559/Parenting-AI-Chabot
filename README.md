Welcome to the GitHub repository for the Parenting Chatbot Project, an advanced chatbot system designed to provide accurate, readable, and accessible parenting advice for parents of newborns up to children one year old. This project leverages the power of language learning models (LLMs) to deliver information from credible sources through a user-friendly interface.

** Project Overview
This chatbot aims to address the challenges parents face in finding reliable and understandable parenting information. The information available is often scattered and of uncertain origin, which can be particularly overwhelming for new parents. By providing a centralized, reliable source of parenting advice, this chatbot assists in making parenting information more accessible and actionable.

System Architecture
Data Sources: Information is sourced from reputable organizations such as the CDC, Just in Time Parenting, and HealthyParents.org.
LLM Support: All nodes within the system are powered by the Gemini 1.5 Flash 001 model, selected to evaluate the feasibility of using freely available models to meet high standards of accuracy, readability, and tone.
Database Segmentation: The information resource is segmented into four databases aligned with specific content categories: child development, child care, health and well-being, and food and nutrition.
Query Handling: A question classifier first determines the appropriate agent to handle incoming queries, which are then processed through specialized agents depending on the content category.
Key Features
Age-Specific Solutions: The chatbot provides solutions that are relevant and practical for different stages of a child’s early development.
Accessibility: Responses are crafted to be easily understandable, suitable for parents of varying reading proficiency levels.
Interactive UI: The chatbot interface allows for simple and direct interaction, ensuring ease of use for all users.
