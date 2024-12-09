Therapy Chatbot for Mental Health Support
Overview

This project focuses on developing an AI-powered therapy chatbot designed to provide support for mental health. The chatbot addresses two main areas:

Suicidal Classification: Classifying user input as suicidal or non-suicidal using a fine-tuned BERT model.
Therapeutic Conversations: Facilitating empathetic and supportive conversations using Meta LLaMA models.
Features
Mental Health Detection: Detects and classifies suicidal tendencies.
Conversational Therapy: Engages in nuanced and empathetic conversations.
Model Optimization: Incorporates techniques like quantization and PEFT for resource efficiency.
Technologies Used
Programming Language: Python
Libraries: Hugging Face Transformers, PyTorch
Models:
BERT (bert-base-uncased) for suicidal classification.
Meta LLaMA (3B and 8B parameters) for therapeutic conversations.
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-repository-name.git
cd your-repository-name
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Download pretrained models and datasets:
Specify the dataset paths in the config.py file.
Usage
1. Running the Classification Model
Run the suicidal classification model:

bash
Copy code
python classify.py
2. Running the Chatbot
Start the chatbot for therapeutic conversations:

bash
Copy code
python chatbot.py
Dataset
Suicidal Classification: Annotated data from Kaggle on mental health-related conversations.
Therapeutic Conversations:
Dataset 1: Conversations between users and psychologists.
Dataset 2: Labeled Q&A pairs between patients and therapists.
Results
The 8B parameter model outperformed the 3B model in accuracy and contextual understanding.
Applied advanced optimization techniques to manage computational demands efficiently.
Future Work
Augment datasets with mixed-emotion examples.
Integrate real-time adaptability and enhanced empathetic responses.
Employ explainability tools (e.g., SHAP or LIME) for model transparency.
Contributors
Bright Ofori
Siri Gangadharaiah
License
This project is licensed under the MIT License. See the LICENSE file for details.