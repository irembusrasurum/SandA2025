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
