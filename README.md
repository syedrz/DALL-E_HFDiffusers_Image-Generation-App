# DALL-E_HFDiffusers_Image-Generation-App
An AI-based image generation app built using Streamlit, Open AI's DALL-E, and huggingface diffusers.

Summary:

- The code utilizes the Streamlit library for building a simple image generation app.
- It imports necessary dependencies such as streamlit, dotenv, os, openai, diffusers, and torch.
- The load_dotenv() function is called to load environment variables, including the OpenAI API key.
Two functions, generate_images_using_openai and generate_images_using_huggingface_diffusers, are defined to generate AI-based images using different models.
- The Streamlit code is organized into three sections based on user choice: "Home", "DALL-E", and "Huggingface Diffusers".
- In the "Home" section, the app displays a title and an expander with information about the app.
- In the "DALL-E" section, the user can enter a text prompt and click a button to generate an image using OpenAI's DALL-E model.
- In the "Huggingface Diffusers" section, the user can enter a text prompt and click a button to generate an image using Huggingface's Diffusers model.

- The generated images are displayed using st.image, and appropriate captions and success messages are shown to the user.


Note: I have modified the code to run model inference for HF diffusers on cpu, so you may have to wait 3-4mins for image to be generated using Diffusers
