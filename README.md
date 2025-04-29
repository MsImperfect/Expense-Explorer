💸 Expense Explorer
Manage your expenses effortlessly with AI-powered invoice reading.
Built using Streamlit, Google Gemini AI, and Python, this web app lets you upload invoice images and ask questions — from itemized breakdowns to total amounts — in natural language.

📌 Features
🖼️ Upload image files (JPG, JPEG, PNG) of invoices
🤖 Uses Gemini 1.5 Flash to process and extract key data
🧾 Ask any kind of question related to your invoice
🧠 Built-in prompt engineering for context-aware responses
🎯 Friendly UI using Streamlit
📌 Personalized AI responses with uniform formatting and itemized outputs
🔁 Ends every interaction with a reminder to reuse Expense Explorer


🚀 How to Run Locally

Step 1:  Clone the repository

Step 2: Run the following commands 

1.
```bash 
pip install -r requirements.txt
```

2. Input your api key here
```bash
genai.configure(api_key = "YOUR GEMINI KEY")
```

3.
```bash
streamlit run app.py
```