# Fine-tuning Gemma for Mobile Deployment

This repository/notebook demonstrates the process of fine-tuning a large language model (LLM), using Gemma 2 as an example, for a non-English language. It then covers the conversion of the fine-tuned model to the `.gguf` format, enabling its deployment and usage on mobile devices. Finally, the repository/notebook provides resources and examples of the model running on a mobile phone.

## Gemma: An Open Language Model by Google

Gemma, developed by Google, is an open model focused on text understanding and generation. Its capabilities enable advanced natural language processing (NLP) tasks, including:

*   Text summarization
*   Translation
*   Creative writing

Gemma is available in various sizes, offering flexibility for developers to select the model that best aligns with their computational resources and target applications. This powerful and accessible tool is designed for researchers and developers working on text-focused AI projects.

## Why Choose Gemma?

Google's Gemma prioritizes safety, efficiency, and performance in AI development. Key advantages include:

*   **Safety:** Trained on a carefully curated and rigorously filtered dataset to minimize harmful content and reduce toxic output.
*   **Efficiency:** Its smaller size facilitates controlled experimentation and faster refinement of safety protocols.
*   **Performance:** Gemma demonstrates strong performance in tasks like reasoning, mathematics, and code generation, while outperforming competitors in safety and efficiency.

Learn more in this [Google AI Blog article](https://blog.google/technology/developers/gemma-open-models/). Also in this [Medium post](https://medium.com/googledeveloperseurope/why-to-choose-gemma-as-an-open-ai-model-37385f8cd20a)

## Fine-tuning Gemma 2 for Greek Text

This repository/notebook demonstrates fine-tuning a pre-trained Gemma 2 Transformer model for Greek text. Transformers are a neural network architecture designed for sequential data. They learn contextual relationships within text to perform various NLP tasks, such as translation and summarization.

We fine-tune the model using a translated dataset. For demonstration purposes, we use Google Translate. However, you can adapt the dataset to your target language using any preferred machine translation service. The included translation cells simplify this process, allowing easy customization of the training data.

## Repository Contents

This repository contains:

*   **[Gemma_final_train_greek.ipynb](Gemma_final_train_greek.ipynb):** A Jupyter notebook detailing the steps for fine-tuning Gemma 2 using Vertex AI, converting it to the .gguf format, and testing it on mobile devices.
*   **README.md:** This file.

## Getting Started

1.  **Clone the repository or download the .ipynb notebook directly**

2.  **Set up Vertex AI:** Set up your Google Cloud Platform (GCP) account and configure Vertex AI.

3.  **Run the Jupyter notebook:** Open and execute the `Gemma_final_train_greek.ipynb` notebook in the Vertex AI environment.

4.  **Deploy to Android:** Follow the instructions in this [Android project](https://github.com/shubham0204/SmolChat-Android) to deploy and run the fine-tuned Gemma model on your mobile device.

## Requirements

*   Google Cloud Platform (GCP) account with Vertex AI enabled.
*   Basic knowledge of machine learning and natural language processing.
*   Familiarity with Jupyter notebooks and Python.
*   Android development environment (for mobile deployment).

## Contributing

Contributions are welcome! Please submit a pull request with your proposed changes.

## License

Apache 2.0
