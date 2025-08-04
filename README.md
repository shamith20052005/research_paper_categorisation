# NLP-Based Research Paper Classification

This project aims to simplify the process of categorizing research papers on submission platforms. By analyzing the title and abstract of papers, our system intelligently predicts the most relevant categories from a set of 57 classes, streamlining the submission workflow and enhancing the user experience.

## Overview

When submitting research papers, authors are often required to manually select categories that best describe their work. Given the vast array of available categories, this task can be daunting and time-consuming. Our solution leverages state-of-the-art NLP models to automate this process, providing category suggestions based on the content of the paper's title and abstract.

## Models Used

We have employed and fine-tuned several advanced models for this task:
- **RoBERTa**: A robustly optimized BERT variant known for its effectiveness in various NLP tasks.
- **DeBERTa**: Enhances BERT and RoBERTa with a disentangled attention mechanism.
- **DeBERTa-Large**: A larger variant of DeBERTa, providing even more powerful contextual embeddings.

An ensemble approach was used to combine the strengths of each model, leading to improved prediction accuracy.

## Performance

The ensemble model achieved an F1 Score of 0.67, indicating a high degree of precision and recall in classifying research papers into the correct categories.

## Project Structure

The project includes the following Jupyter notebooks:

- **DeBERTa Script**: [Link](https://github.com/KrishnaMahalka/kriti24/blob/9cea4944176256e59cfbd3223c13ac55fb570b8d/deberta.ipynb)
- **DeBERTa Training Script** (Overfit Model): [Link](https://github.com/KrishnaMahalka/kriti24/blob/e711dc5c31935855064b6f85cf631fa18dff36af/deberta6.ipynb)
- **DeBERTa-Large Script**: [Link](https://github.com/KrishnaMahalka/kriti24/blob/33118842747759544ac7f06259deebe7553ff8c7/debertalarge.ipynb)
- **RoBERTa Script**: [Link](https://github.com/KrishnaMahalka/kriti24/blob/c55e55812723cdcf8ca711d1e826607e3ae63a4f/roberta3.ipynb)
- **Inference Notebook**: [Link](https://github.com/KrishnaMahalka/kriti24/blob/master/%5BINFER%5D%20Kameng.ipynb)

Each notebook contains detailed steps for model training, fine-tuning, and inference.

## Future Work

- **Web Application**: Development of a Flask-based web application to make the model accessible to a broader audience.
- **Model Enhancement**: Ongoing research to further improve the model's accuracy and efficiency.

## Contributions and Queries

This project was done by Team Kameng.
We welcome contributions from the community to make this project more robust and versatile. For queries or contributions, please contact:

- **Malabh Bakshi**
- Email: [malabhbakshi61@gmail.com](mailto:malabhbakshi61@gmail.com)
