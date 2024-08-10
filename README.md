# final-Project-Interview-Insights-Group-24-
interview Insights
                                         Interactive Interview Question Generator
Table of Contents
•	Overview
•	Features
•	Requirements
•	Installation
•	Usage
•	Troubleshooting
•	License
•	Acknowledgments


link to our video below
https://youtu.be/v0uwl4S4JBQ?si=C4N7aK7jWSw-OKUL


Overview
This project is an interactive application designed to generate and evaluate interview questions across various fields such as Data Science, Finance, Nursing, and more. Users can specify the field, number of questions, and preferred language for the interview. The questions are generated using a language model, and the user’s answers are evaluated, providing feedback on their responses.

Features
•	Field Selection: Choose from a variety of fields like Data Science, Finance, and Nursing.
•	Customizable Question Count: Specify the number of interview questions to be generated.
•	Language Support: Supports multiple languages for question generation and answer evaluation.
•	Interactive Interface: User-friendly interface that guides you through the interview process.
•	Answer Evaluation: Provides feedback on your answers based on the generated questions.

Requirements
•	Python 3.10 or higher
•	Torch 2.4.0
•	Unsloth 
•	Xformers
•	Various NLP and utility libraries

Installation
Install the required Python packages:\
pip install torch==2.4.0
pip install unsloth[colab-new]@git+https://github.com/unslothai/unsloth.git
pip install xformers==0.0.25
pip install pyngrok pydub google-cloud-translate langdetect transformers beautifulsoup4 requests

1.	Clone the necessary repositories:
git clone https://github.com/unslothai/unsloth.git


Usage
1.	Run your Colab notebook.
2.	Enter the field of interest, the number of questions, and the preferred language.
3.	Generate the questions and answer them interactively.
4.	Review the evaluation and feedback provided.

Troubleshooting
•	Cache Errors: If you encounter cache-related errors, ensure that the model’s cache is properly initialized before generation. Ensure compatibility between the installed versions of Torch, Unsloth, and Xformers.
•	
License
This project is licensed under the MIT License. See the LICENSE file for more details.
351265252
Acknowledgments
Special thanks to the contributors and the open-source community for their support in building this project.



