# Mental Health Chatbot

Welcome to the **Mental Health Chatbot** repository! This chatbot is designed to provide support and information related to mental health. It leverages natural language processing (NLP) to understand user queries and deliver appropriate responses, creating a safe space for users to express their feelings and receive helpful advice or resources.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Conversational Interface**: Interacts with users through a friendly and intuitive chat interface.
- **Mental Health Resources**: Provides valuable information and resources on mental health.
- **Anonymity**: Ensures user conversations remain private and secure.
- **Customizable Responses**: Easily adaptable to include more topics or modify existing ones.

## Installation

To get started with the Mental Health Chatbot, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/nilavanan-ver-4/Mental-health-Chatbot.git
   cd Mental-health-Chatbot
   ```

2. **Create and activate a virtual environment**:
   ```sh
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

4. **Install additional dependencies**:
   ```sh
   python -m spacy download en_core_web_sm
   pip install -q -U google-generativeai
   python -m spacy download xx_ent_wiki_sm
   ```

5. **Run the Python application**:
   ```sh
   python app.py
   ```


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

```
