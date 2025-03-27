# Laptop Recommendation Chatbot (Full RAG)  
Dynamic Laptop Recommendations Powered by Real-Time Data and Advanced AI  

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.8%2B-brightgreen.svg)](https://www.python.org/)

---

## ✨ About the Project  
The Laptop Recommendation Assistant with Full RAG leverages a dynamic dataset of 900+ laptops stored in a `.csv` file, updated weekly to ensure recommendations are always accurate and up-to-date. By combining real-time retrieval from the dataset with the contextual understanding of GPT models, the chatbot delivers precise, data-driven, and personalized laptop recommendations tailored to user preferences.  

---

## 🔍 Key Features  
- **Dynamic Dataset Integration**: Uses a `.csv` file containing 900+ laptop details updated weekly to maintain accuracy.  
- **Real-Time Data Retrieval**: Access the latest laptop specifications, including performance, portability, battery life, and pricing.  
- **AI-Powered Personalization**: GPT models analyze user input to provide highly contextual and relevant suggestions.  
- **Scalable Data Handling**: Handles large datasets efficiently to ensure quick responses and optimal performance.  
- **Customizable Filters**: Allows filtering laptops based on budget, use case, and specific features like GPU or RAM size.  

---

## 🛠️ Tech Stack  
- **Language**: Python  
- **Frameworks/Libraries**: Pandas, OpenAI API, SentenceTransformers, Huggingface_hub, chromadb 
- **APIs/Models**: OpenAI's GPT-4/ GPT-4o/ GPT-4o-mini or Huggingface Mistral API for generation  
- **Database**: `.csv` file as a dataset source  
- **Tools Used**: Jupyter Notebook  

---

## 🧪 Example Use Cases  
- "Find me the best laptop for video editing under ₹1,50,000 with an RTX GPU."  
- "What is the lightest laptop with a 14-inch screen and long battery life?"  
- "Recommend a gaming laptop with a 144Hz display and Intel i7 processor."  

---

## 📸 Sample Output
### 1. User Input Interface
![User Input Interface](Sample%20Code%20Output%20Screenshots/Sample%20Code%20Output%202.png)

### 2. Recommendation Output
![Recommendation Output](Sample%20Code%20Output%20Screenshots/Sample%20Code%20Output%201.png)

---

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Docker (optional, for containerized deployment)

### Installation

1. Navigate to the project directory:
cd Laptop_Recommendation_Chatbot_RAG

2. Install the required dependencies:
pip install -r requirements.txt

- Please note: HuggingFace/Gemini API keys are required for the project to function. You can obtain them from the their respective website and change the same in the code.

3. Run the main file from Jupyter environment:
"Laptop_recommendation_RAG.ipynb"

---

## 📖 Documentation
No documentation will be made available for this project since this project only uses technologies that already have their own documentation. Please refer to the following links for more information:
- [Gemini](https://ai.google.dev/gemini-api/docs/models/gemini)
- [HuggingFace/MistralAI](https://huggingface.co/mistralai/Mixtral-8x7B-Instruct-v0.1)
- [ChromaDB](https://docs.trychroma.com/)
- [sentence-transformers](https://www.sbert.net/docs/)
- [Pandas](https://pandas.pydata.org/docs/)

---

## 🛠️ Challenges/Issues Faced with fixes
- [Issue 1](GPT model Generation is probabilistic in nature. Meaning response from GPT for the same Query might be different. This nature of GPT models are
not usually accepted by general user. So I have added 'Temperature' parameter to the requests with low value to make the models perform in thier lowest
probabilistic settings, so it generally provides reproducable output)

- [Issue 2](Reworked on the logic and updated prompts to include few instructions to generate more relevant answers to the user queries. This was done to improve the quality of the answers to the user queries.)

---

## 🚀 Future Scope  
- Automate weekly updates with real-time scraping from trusted e-commerce sites.  
- Enhance dataset fields to include additional metrics like warranty details and user reviews.  
- Introduce dynamic API integrations for live pricing and stock availability.  

---

## 🛡️ Conclusion  
The Laptop Recommendation Assistant with Full RAG offers dynamic, real-time insights powered by a large dataset and advanced GPT models. This approach ensures recommendations are always accurate, personalized, and reflective of the latest market trends. Whether for gaming, productivity, or casual use, the chatbot is a reliable tool for finding the perfect laptop.  

---

## 🛡️ License
Distributed under the MIT License. See `LICENSE` for more information.

---
