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



# Week 9: Integrated AI Interface
This project merges the previous weeks' Chatbot and Generative Art projects into a single, unified Streamlit application.

### Features
- **Dual Mode:** Users can switch between "Chat Mode" and "Art Mode" using a sidebar menu.
- **Unified Engine:** Runs on Google Colab using free models from Hugging Face.

### Implementation
- **Chat:** Built with the `transformers` library using models like Flan-T5.
- **Art:** Powered by `diffusers` using the Stable Diffusion model.

# Week 10: Creativity Parameters & Optimization

This week focuses on how hyper-parameters affect the outputs of Generative AI.

### Tested Parameters
1. **Temperature:** Controlled the randomness. [cite_start]Lower values (0.2) made the chatbot more factual; higher values (0.9) made it more creative but less predictable.
2. **Max Length:** Adjusted the length of the generated responses.
3. **Top_p:** Used to filter the cumulative probability of next-token candidates.

### Conclusion
By optimizing these values, we can balance the "Science" (accuracy) and "Art" (creativity) of the model's output.

# Week 11: Image Processing & Filters

In this phase, we added an extra layer of "Art" by allowing manual manipulation of AI-generated images.

### Features
- **Filter Integration:** Used `Pillow` and `OpenCV` to apply artistic styles.
- **User Choice:** A dropdown menu in the Streamlit UI lets users choose between:
  - **Grayscale:** For a classic look.
  - **Blur:** For a soft, dreamlike effect.
  - **Edge Detection:** To highlight the structural "Science" of the image.
 
 # Final Project: The Science & Art AI Suite

This is the final version of the course project, representing a complete pipeline from setup to deployment.

### Final Steps
- **UI Finalization:** Cleaned up the interface for a better user experience.
- **Deployment:** The app is hosted live using **Streamlit Cloud**.


### Technologies Used
-Google Colab (Development) 
- Streamlit (Web UI)
- Hugging Face Models (AI Engine)

# Week 13: Containerization with Docker

This bonus week focuses on making the application portable using Docker.

### Tasks
- Created a `Dockerfile` to package the Streamlit app.
- Defined all dependencies (transformers, diffusers, pillow) to ensure the app runs on any environment.

### Why Docker?
It ensures that the "Science and Art" app functions identically regardless of the host operating system or local library versions.
  
