# Week4
ScinceandArt

This week, I prepared the necessary environment for the Generative AI project .

- The Google Colab environment was created.
- The `transformers`, `torch`, `streamlit`, and `diffusers` libraries were installed.
- The `.ipynb` file showing the installations was added to this folder.

# Week5

Completed Milestones
-Model Integration: A free-tier Hugging Face model was selected and integrated via the transformers library to serve as the generative core.

-Model Used: google/flan-t5-base

-Inference Functionality Established: A dedicated Python function (get_chatbot_response_t5) was engineered to handle user prompts and manage the model's text generation process.

-Decoding Parameters Optimized: Crucial decoding strategies were applied to mitigate common issues such as repetitive or nonsensical output, ensuring a higher quality of response.

-Key Parameters: Beam Search (num_beams=3) and Repetition Penalty (repetition_penalty=1.5).

-Demonstration Prepared: The final .ipynb notebook includes sample interactions, demonstrating the model's ability to process various user questions and generate clear responses.

# Week6

Streamlit Chatbot Interface (FLAN-T5)

This project creates a chatbot web interface using Streamlit and a Large Language Model (LLM) from Hugging Face: the FLAN-T5-Base model. It is designed to be easily deployed in cloud environments like Google Colab and made accessible via a public URL.

Project Summary

Model Used: Hugging Face google/flan-t5-base. This is an LLM used for text-to-text generation.

Interface: The web interface is built with Streamlit.

Performance: The model is optimized by being loaded only once using the @st.cache_resource function.

Accessibility: The application is exposed to the internet via localtunnel when running on Colab.


# Week 7
Generative Art with Stable Diffusion

This week, we created AI images from text prompts using the Stable Diffusion model. The Hugging Face 'diffusers' library was utilized.

Used Prompts

A futuristic city in watercolor style, detailed, concept art

An astronaut riding a horse on Mars, cinematic lighting, photo realistic

A medieval library with glowing books, fantasy art, volumetric light

Example Outputs



<img width="512" height="512" alt="f77d1e3d-aa88-4a1e-bb71-1a880039b599" src="https://github.com/user-attachments/assets/3d99097d-e448-45c4-a844-c14605ef64bb" />
<img width="512" height="512" alt="dd5b8a58-0acc-49af-a9da-26573b9a3c89" src="https://github.com/user-attachments/assets/cf8d5b0e-dee7-466f-8935-c274947e26fc" />
<img width="512" height="512" alt="1a924cf7-6e73-4253-a49a-452074bbc7cb" src="https://github.com/user-attachments/assets/28091ad7-69b5-4248-8bc9-719df07fd635" />
