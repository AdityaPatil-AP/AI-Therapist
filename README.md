# AI-Therapist

AI-Therapist is an advanced system that utilizes LSTM networks and NLP techniques to provide personalized mental health support. The system detects emotions from text input on how your day went or how you are currently feeling and offers appropriate advice and recommendations, including song recommendations. It also maintains a log of emotions with timestamps to track emotional patterns over time.

## Problem Statement

The goal of this project is to create a system that accurately detects and understands emotions expressed in text input and provides customized solutions and recommendations. The system aims to improve mental well-being by offering empathetic responses, practical guidance, and personalized interventions based on emotional patterns.

## Features

- **Emotion Detection:** The system utilizes bidirectional LSTM networks and NLP techniques to accurately detect emotions expressed in text input. We explored other machine learning models such as Random Forests, Decision Tree Model, and Support Vector Machines, but found that the bidirectional LSTM model provided the best accuracy and performance.
- **Customized Solutions:** Based on the detected emotions, the system provides personalized advice and guidance to address the user's emotional state. The solutions are tailored to the specific emotions expressed in the input text, allowing for a more effective and empathetic response.
- **Song Recommendations:** The system suggests songs based on the detected emotions to uplift the user's mood and provide emotional support. The song recommendations are curated to align with the user's emotional state, aiming to create a positive and soothing experience.
- **Emotion Tracking:** The system maintains a log of emotions with timestamps, allowing for tracking and analysis of emotional patterns over time. This feature enables healthcare professionals to assess an individual's emotional well-being during subsequent appointments, providing insights into their emotional journey and progress.

## System Workflow

1. **User Input:** The user writes about their day and the incidents that occurred, along with their feelings about those incidents.
2. **Emotion Detection:** The AI Therapist model, powered by bidirectional LSTM networks and NLP techniques, processes the input text and accurately detects the expressed emotions. This model was chosen for its ability to capture context and dependencies in sequential data, making it well-suited for analyzing text-based emotional expression.
3. **Emotion Log:** The system simultaneously stores the log of emotions, enabling future assessments by healthcare professionals during subsequent appointments. The log includes timestamps, allowing for chronological tracking of emotional patterns and progress over time.
4. **OpenAI Integration:** The system is integrated with the OpenAI API, which provides appropriate solutions and recommendations if the user is not feeling well based on the output of the AI Therapist model. This integration enhances the system's language capabilities and provides detailed explanations and practical guidance to users.
5. **Continuous Monitoring:** The system ensures ongoing monitoring of individuals' emotional well-being through the combination of emotion tracking and personalized interventions. By analyzing the emotion log and providing tailored solutions, the system supports individuals in improving their emotional well-being.

## Tools and Technologies Used

- **Programming Language:** Python
- **Machine Learning Models:** Bidirectional LSTM, Random Forests, Decision Tree Model, Support Vector Machines
- **NLP Techniques:** GLoVe (Global Vectors for Word Representation)
- **API:** OpenAI

## Installation and Usage

To use the AI-Therapist system, follow these steps:

1. Clone the repository to your local machine.
2. Set up a Python environment and install the necessary dependencies.
3. Run the system using the provided script.
4. Input your thoughts and feelings about your day to receive personalized mental health support and recommendations.

## Contributors

- Aditya Patil
- Anuja Deshpande
- Dev Bohra
- Surabhi Deshpande

Feel free to contribute to this project by submitting bug reports, feature requests, or pull requests.

Please note that this project is intended for educational and informational purposes and should not replace professional mental health advice. If you are experiencing mental health issues, please seek help from a qualified healthcare professional.

