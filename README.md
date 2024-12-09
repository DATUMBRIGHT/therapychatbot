Here's an overview of the Therapy Chatbot for Mental Health Support project:

Project Overview:
- This project focuses on developing an AI-powered therapy chatbot designed to provide support for mental health.
- The chatbot addresses two main areas:
  1. Suicidal Classification: Classifying user input as suicidal or non-suicidal using a fine-tuned BERT model.
  2. Therapeutic Conversations: Facilitating empathetic and supportive conversations using Meta LLaMA models.

Key Features:
1. Mental Health Detection: The chatbot can detect and classify suicidal tendencies in user input.
2. Conversational Therapy: The chatbot engages in nuanced and empathetic conversations to provide mental health support.
3. Model Optimization: The project incorporates techniques like quantization and PEFT to optimize the models for resource efficiency.

Technologies Used:
- Programming Language: Python
- Libraries: Hugging Face Transformers, PyTorch
- Models:
  - BERT (bert-base-uncased) for suicidal classification
  - Meta LLaMA (3B and 8B parameters) for therapeutic conversations

Installation:
1. Clone the repository: `git clone https://github.com/DATUMBRIGHT/therapychatbot`
2. Install dependencies: `pip install -r requirements.txt`
3. Download the pretrained models and datasets, and specify the dataset paths in the `config.py` file.

Usage:
1. Running the Classification Model: `python classify.py`
2. Running the Chatbot: `python chatbot.py`

Datasets:
- Suicidal Classification: Annotated data from Kaggle on mental health-related conversations.
- Therapeutic Conversations: Dataset 1: Conversations between users and psychologists. Dataset 2: Labeled Q&A pairs between patients and therapists.

Results:
- The 8B parameter Meta LLaMA model outperformed the 3B model in accuracy and contextual understanding.
- Advanced optimization techniques were applied to manage computational demands efficiently.

Future Work:
- Augment datasets with mixed-emotion examples.
- Integrate real-time adaptability and enhanced empathetic responses.
- Employ explainability tools (e.g., SHAP or LIME) for model transparency.

Contributors:
- Bright Ofori
- Siri Gangadharaiah

License:
- This project is licensed under the MIT License.