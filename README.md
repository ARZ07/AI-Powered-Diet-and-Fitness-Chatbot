# AI-Powered Diet and Fitness Chatbot 

A personalized diet and workout chatbot using a **fine-tuned LLM** and **Google Gemini integration**.  
This project uses a fine-tuned `gpt2` model along with `gemini-pro-latest` to provide **accurate recommendations** and **interactive chatbot conversations**.

## Features 

- Provides **personalized diet and workout plans** for users  
- Takes user details such as **diet and workout timings** to create tailored plans  
- Integrated **Gemini-Pro model** for natural conversations and access to additional web-based info  
- Fine-tuned `gpt2` model for **efficient and accurate predictions** based on a large diet and workout dataset  

## Dataset 

- nutritional-values-for-common-foods-and-products from kaggle
- gym-members-exercise-dataset from kaggle 


## Technologies 

- Kaggle API for dataset access  
- Pandas for data processing  
- Transformers for fine-tuning GPT-2  
- Google Generative AI for Gemini-Pro API  

## How It Works 

1. **Data Gathering:** Collect food nutrition and gym exercise datasets from Kaggle  
2. **Model Selection:** Use `gpt2` to reduce resource requirements, fine-tuned for this application, and integrated with Gemini-Pro for conversational capabilities  
3. **Model Training:** Fine-tune `gpt2` using Transformers to improve accuracy and efficiency  
4. **User Data Collection:** Gather user info such as diet timings and workout hours to calculate calories consumed and burned  
5. **Personalized Recommendations:** Fine-tuned GPT-2 analyzes the user data to generate tailored diet and workout plans  
6. **Interactive Chat:** Gemini API provides chatbot functionality, web access for clarifications, and additional recommendations  
