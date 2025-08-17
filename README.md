# 🌱 AgriNLP-Chatbot

A simple chatbot that can **summarize and answer questions** from agriculture-related books using Natural Language Processing (NLP).

## 📌 Project Overview
Farmers, students, and agriculture professionals often need **quick answers** from long agricultural books.  
This project builds a chatbot that:
- Reads agriculture books  
- Finds the most relevant parts  
- Gives short answers or summaries  
- Provides a simple web interface to chat

## ⚙️ How It Works
1. **Data Collection**  
   - Downloads free agriculture e-books from *Project Gutenberg*.  

2. **Preprocessing**  
   - Cleans text (removes headers, footers, extra notes).  
   - Splits books into useful paragraphs.  

3. **Embedding & Search**  
   - Turns text into vectors using **Sentence Transformers**.  
   - Stores them in **FAISS** for fast search.  

4. **Models Used**  
   - **BART** → for summarization (long answers).  
   - **BERT** → for question answering (short facts).

## 🚀 Features
- ✅ Ask agriculture-related questions  
- ✅ Get answers directly from e-books  
- ✅ Summarize long topics 
- ✅ Simple web-based chatbot interface

## 🛠️ Tech Stack
- **Python**  
- **Libraries:** `transformers`, `torch`, `faiss-cpu`, `sentence-transformers`, `datasets`, `gradio`  

## 📂 Project Files
- `Agriculture_Chatbot.ipynb` → Main notebook with all code  
- `Project_Document_Agriculture_chatbot.pdf` → Project documentation

## 🔮 Future Improvements

- Add more agriculture books and datasets

- Train models more deeply for better accuracy

- Support multi-turn conversations (remember chat history)

- Provide longer summaries in bullet points

## 🟢 Run in Google Colab (Easiest)

- Go to Google Colab.

- Upload the file Agriculture_Chatbot.ipynb.

- The notebook will open.

- Click Runtime → Run all

- The chatbot will start. At the end, a link will appear — click it to open the Gradio Chatbot in a new tab.

## 👥 Authors

- Jayamini Hewawasam

- Shashikala Rajapaksha

  

5. **User Interface**  
   - Built with **Gradio** for easy interaction.  
