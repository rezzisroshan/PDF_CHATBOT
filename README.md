# PDF Chatbot

## Project Overview

This chatbot reads any recipe PDF you upload and answers your questions directly from the recipe, without guessing. You can ask for ingredients, steps, cooking times, or tools, and the chatbot will pull the information exactly as written in the recipe.  

It’s built with LangChain, ChromaDB, Hugging Face embeddings, and FLAN-T5, with a Gradio interface for easy interaction.  

---

## Features
- Extracts **ingredients** with quantities and units.
- Lists **step-by-step instructions** clearly.
- Identifies **tools or equipment** mentioned in the recipe.
- Finds **cooking or preparation times**.
- Answers other recipe-specific questions.
- Works entirely from the provided recipe PDF, no outside guessing.

---

## Tools and Technologies
- **LangChain** for text retrieval and prompt handling
- **ChromaDB** for vector storage
- **Hugging Face** embeddings (`all-MiniLM-L6-v2`)
- **FLAN-T5** for natural language answers
- **Gradio** for the chatbot UI
- **PyPDF** for reading recipe PDFs

---

## How to Run
```bash
# Clone the repo
git clone https://github.com/yourusername/RECIPE_PDF_CHATBOT.git

# Navigate into the folder
cd RECIPE_PDF_CHATBOT

# Install dependencies
pip install -r requirements.txt

# Place your recipe PDF inside the data folder

# Run the chatbot
python app/recipe_pdf_chatbot.py
```

Once running, a Gradio interface will open in your browser where you can type your questions.

---

## Example Questions
- What are the ingredients for this recipe?
- How long does it take to cook?
- What tools do I need to make this?
- Give me the step-by-step instructions.

---

## Future Improvements
- Allow uploading PDFs directly from the Gradio UI.
- Add multi-recipe support.
- Deploy online so it runs without local setup.

---

## Contact
Author: Kewal Roshan Ezra  
Email: rezzisroshan@gmail.com  
LinkedIn: [Kewal Roshan Ezra](https://linkedin.com/in/kewalroshanezra)
