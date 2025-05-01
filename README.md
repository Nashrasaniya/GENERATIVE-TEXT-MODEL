# GENERATIVE-TEXT-MODEL

"Company":CODTECH IT SOLUTIONS

"NAME":MOHAMMED NASHRA SANIYA

"INTERN ID":CODF167

"DOMAIN":ARTIFICIAL INTELLIGENCE MARKUP LANGUAGE

"DURATION:"4 WEEKS

"MENTOR":NEELA SANTHOSH

# PROJECT DESCRIPTION

This project is a part of the Codtech Internship – Task 4, which focuses on developing a Generative Text Model using GPT-based architecture. Specifically, we use the lightweight and efficient DistilGPT2 model to generate human-like paragraphs based on user-defined input topics or sentences.

The system prompts the user to enter a topic or a starting paragraph. Based on the input, it generates a continuation that is grammatically coherent, contextually relevant, and stylistically similar to natural human writing. The model operates entirely offline after a one-time manual download of required files from Hugging Face, making it ideal for low-resource or disconnected environments.

This solution showcases the real-world capability of Natural Language Generation (NLG) using transformer models and serves as a strong foundation for building content generation tools, AI writing assistants, educational applications, and more.

# FEATURES

-  Loads DistilGPT2 model from local directory (offline mode).
  
-  Accepts both single-line and paragraph prompts from the user.
  
-  Generates human-like, contextually relevant text using transformers.
 
-  Seeded for reproducible results.
 
-  Works without needing an internet connection (offline ready).

#  Install Dependencies

Ensure you have Python 3.8+ and run:

    pip install torch transformers

Optional for Jupyter users:

   pip install ipywidgets tqdm

#  Download the Model (Manual Step)

Go to: https://huggingface.co/distilgpt2/tree/main

Download the following files and save them in a folder named distilgpt2_local:

1. config.json

2. pytorch_model.bin

3. tokenizer.json

4. tokenizer_config.json

5. vocab.json

## 🔧 Model Setup Instructions

To run this project locally, you need to manually download the `distilgpt2` model from Hugging Face and place it in the same directory.

# Step-by-step:

1. Visit: https://huggingface.co/distilgpt2/tree/main
   
2. Download the following files:
   
   - `config.json`
     
   - `merges.txt`
     
   - `pytorch_model.bin`
     
   - `tokenizer_config.json`
     
   - `vocab.json`
     
3. Create a folder named `distilgpt2_local` and place all the files inside it.
  
4. Make sure your local path in the code matches this folder.

The project will then run fully offline using the locally saved model.


# Run the Notebook

Open text_generator.ipynb in VS Code or Jupyter and follow the instructions to generate text.

# Example

Prompt:

Climate change is one of the most pressing challenges facing humanity today.

Generated Output:

Climate change is one of the most pressing challenges facing humanity today.

"Today, our climate is changing," said Dr. Richard M. Green, chief scientist at the CDC...

# Deliverable

1. A notebook that accepts a user prompt (single line or paragraph).

2. Generates a coherent continuation using DistilGPT2.

3. Runs offline using a local copy of the model.

# requirements.txt

1.transformers==4.40.1

2. torch>=1.13.0
   
3.ipywidgets>=7.6.0

4.notebook

# Internship Credit

Completion of this task contributes to your Codtech Internship Certificate.
