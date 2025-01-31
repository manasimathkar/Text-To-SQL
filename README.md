# SQLGenPro - Text-to-SQL Conversion Web App

## Overview
SQLGenPro is a Streamlit web application that leverages OpenAI's GPT-4 to enable users to convert natural language queries into SQL commands. This tool is designed to democratize data access by allowing non-technical users to interact with databases without needing extensive SQL knowledge, thereby enhancing productivity and decision-making in data-driven environments.

## Features
- **Natural Language to SQL Conversion:** Utilizes GPT-4 to interpret and convert user input into optimized SQL queries.
- **User Authentication:** Secure login and session management to ensure data security.
- **Intuitive User Interface:** Easy-to-navigate interface for entering queries and viewing SQL outputs and query history.
- **Advanced SQL Optimization:** Ensures high efficiency and accuracy of generated SQL queries.

## Tech Stack
- **Frontend:** Streamlit
- **Backend:** Python, Databricks
- **APIs:** OpenAI
- **Database:** Snowflake (via Databricks connections)
- **Deployment:** AWS EC2

## Prerequisites
- Python 3.10 or newer
- Streamlit
- An OpenAI API key
- Databricks and Snowflake accounts

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/SQLGenPro.git
