# Text-to-SQL
This project is a web-based application that converts natural language questions into SQL queries and retrieves data from a local SQLite database. It leverages Google's Generative AI (Gemini model) to interpret the user's input and dynamically generate the appropriate SQL commands.

# Features:
- Natural Language to SQL Conversion: Users can input questions in plain English, and the app generates SQL queries to retrieve the corresponding data from an SQLite database.
- Google Generative AI (Gemini): The project utilizes Google's advanced generative AI model to convert text input into executable SQL queries.
- Streamlit Interface: A simple and interactive web application is built using Streamlit, allowing users to input their queries and see results in real-time.
- SQLite Integration: A local SQLite database is used to store and query data, simulating how SQL works in practical applications.

# Key Technologies:
- Python
- Streamlit
- Google Generative AI (Gemini Model)
- SQLite
- dotenv (for secure environment variable management)

  ## Step-by-Step Guide

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/text-to-sql.git
   cd text-to-sql

2. # Set up a virtual environment (optional but recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
