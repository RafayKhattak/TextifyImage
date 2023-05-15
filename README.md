# TextifyImage
TextifyImage is a web application that leverages the power of AI to generate images from text prompts. By utilizing OpenAI's DALL-E model and Huggingface's Stable Diffusion model, TextifyImage allows users to transform their textual descriptions into stunning visual representations.
![Uploading Screenshot (449).png…]()
## Features
- DALL-E Image Generation: TextifyImage utilizes OpenAI's DALL-E model to generate high-quality images based on user-provided text prompts.
- Huggingface Diffusers Image Generation: TextifyImage also leverages Huggingface's Stable Diffusion model to generate AI-based images from text prompts.
- Streamlit User Interface: The application provides an intuitive user interface powered by Streamlit, making it easy for users to interact with and generate images.
## Installation
To run TextifyImage locally, follow these steps:
1. Clone the repository:
```
git clone https://github.com/your-username/TextifyImage.git
cd <repository>
```
2. Install the required dependencies:
```
pip install -r requirements.txt
```
3. Set up the OpenAI API key:
- Sign up for an OpenAI account and obtain your API key.
- Set the API key as an environment variable or directly in the code (replace YOUR_OPENAI_API_KEY in the code):
```
openai.api_key = 'YOUR_OPENAI_API_KEY'
```
4. Download Stable diffusion v1.5 weights and save in project directory:
```
wget https://huggingface.co/runwayml/stable-diffusion-v1-5/resolve/main/v1-5-pruned-emaonly.ckpt
```
5. Run the application:
```
streamlit run app.py
```
## Acknowledgments
- This project was inspired by the capabilities of OpenAI's DALL-E and Huggingface's Stable Diffusion models.
- I would like to thank the developers and contributors of OpenA and Huggingface for their invaluable work and open-source contributions.


