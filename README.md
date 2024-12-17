# Nurse-Match-Chatbot - *Ask Margot*

## Overview  
The **Ask Margot Chatbot** is an AI-powered tool designed to answer hospital-related questions efficiently and accurately. By leveraging OpenAI's API, the chatbot delivers real-time responses, showcasing the seamless integration of advanced AI tools with Python.  

This project aims to simplify interactions by providing quick, intuitive answers to common hospital queries, making it a useful companion for nurses, administrators, and other healthcare professionals.  

## Features  
**Easy to Use:** Start the chatbot however you'd like -- with a quick 'hi' or just get straight to the point.  
**Interactive Chat:** Engage in a natural conversation to get instant answers to hospital-related questions. 
**Robust Logging:** Ensures reliability with operation and error tracking for debugging and analysis.  
**Seamless AI Integration:** Utilizes OpenAI's API for fast and accurate real-time responses.  


## Setup  
1. Clone this repository:  
   git clone https://github.com/kimng216/Nurse-Match-Chatbot.git
   cd Nurse-Match-Chatbot
2. Install the required dependencies:  
   pip install -r requirements.txt
3. Add your OpenAI credentials in a `.env` file:  
   ASSISTANT_ID=<Your OpenAI Assistant ID>
   OPENAI_API_KEY=<Your OpenAI API Key>
4. Run the chatbot:  
   python chatbotCode.py

## Project Structure  
- **README.md:** Project documentation (you're reading it).  
- **chatbot.py:** Main script that runs the chatbot.  

## Usage 
1. Start the chatbot by running `python chatbot.py`.  
2. Enter your hospital-related question or query.  
3. Type `exit` anytime to quit the conversation.  


## Future Enhancements  
- **Custom Responses:** Fine-tune the chatbot for specific hospital-related use cases.  
- **Improved UX:** Add a web interface for broader accessibility.  
- **Extended Data Sources:** Integrate additional healthcare databases for richer answers.  
