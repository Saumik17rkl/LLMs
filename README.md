# LLM Text Generator with Gradio  

This project provides an interface for generating text using Google's **Gemma-2-2b-it** language model. The application is built with **Gradio** for easy interaction.  

## Features  
- Uses **Google's Gemma-2-2b-it** model for text generation.  
- **Gradio-based UI** for simple and interactive text input/output.  
- Runs **locally** without external API dependencies.  

## Installation  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```  
2. Create a virtual environment (optional but recommended):  
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```  
3. Install dependencies:  
   ```bash
   pip install torch transformers gradio
   ```  

## Usage  
1. Set your Hugging Face API token inside the script:  
   ```python
   os.environ["HF_TOKEN"] = "Your_Hugging_Face_API_Key"
   ```  
2. Run the script:  
   ```bash
   python Deploy_LLM_Gradio.py
   ```  
3. Open the **Gradio UI** in your browser and start generating text!  

## Acknowledgments  
- [Hugging Face](https://huggingface.co/) for providing pre-trained models.  
- [Gradio](https://www.gradio.app/) for the interactive UI framework.  
