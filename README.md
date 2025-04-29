# Text-to-image-conversion-

**Text-to-Image Generation Using Stable Diffusion**

This project demonstrates the use of Stable Diffusion, a state-of-the-art generative AI model, for creating high-quality images from natural language text prompts. By leveraging the power of Hugging Face's diffusers library and pre-trained models, this project allows users to generate detailed and photorealistic images with minimal effort.

Developed sentiment classification models using TF-IDF(**Term Frequency – Inverse Document Frequency**), Logistic Regression, and Naive Bayes algorithms, optimizing performance and achieving strong evaluation metrics. 


**Key Features:**

**Text-to-Image Generation:** Convert text descriptions into stunning, highly detailed images using Stable Diffusion.

**Pre-Trained Model:** Utilizes the pre-trained models provided by diffusers, such as runwayml/stable-diffusion-v1-5 or stabilityai/stable-diffusion-2-1.

**GPU Support:** Automatically detects and utilizes GPU (if available) for faster image generation.

**Customizable Prompts:** Generate images based on any creative idea or concept described in natural language.

**Image Display and Manipulation:** Visualize generated images using Matplotlib and optionally save or further manipulate them.


**Working Methodology :**

**Setup and Initialization:**

    The system checks for GPU availability and sets the computation device accordingly.
    A pre-trained Stable Diffusion model is loaded using the diffusers library.
    
**Generate Images:**

    Users provide a text prompt describing the desired image.
    The Stable Diffusion pipeline processes the prompt to generate an image.
    
**Display and Further Use:**

    The generated image is displayed using Matplotlib.
    The image can be saved, resized, or further manipulated.


