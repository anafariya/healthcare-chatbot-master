# HealthCare ChatBot

## Introduction

The HealthCare ChatBot is a conversational interface designed to assist users in assessing their health symptoms, providing information about potential illnesses, and offering precautionary measures. This application utilizes machine learning algorithms to analyze user-input symptoms and generate relevant insights.

## Features

- Symptom identification and analysis
- Severity assessment
- Recommendation for precautionary measures
- Integration with decision tree classifier for prognosis prediction
- Voice assistance for a user-friendly experience

## Prerequisites

Before you begin, ensure you have the following installed:

- Python (version x.x.x)
- Required Python libraries (NumPy, Pandas, Scikit-learn, etc.)

## Installation

Clone the repository:

   ```bash
   git clone https://github.com/yourusername/HealthCare-ChatBot.git
   
Navigate to the project directory:
 
  ```bash
   cd HealthCare-ChatBot
   ```


Install dependencies:

```bash
pip install -r requirements.txt
```
Usage

Run the main application script:

```bash
python main.py
```
Follow the on-screen prompts to interact with the ChatBot.

# *Configuration*
Update the Data/Training.csv and Data/Testing.csv files with the latest health data.

Customize voice settings in the pyttsx3.init() function in the tree_to_code function.

# *License*
This project is licensed under the MIT License.

