#String Data Type Inference

This Python project demonstrates how to use multiple 'machine learning' (ML) models to infer the data type of a given string. The project provides a collection of ML models trained on various data types, including numeric, categorical, and text data. By utilizing these models, you can automatically classify the input string into one of the predefined data types.

##Features
* Infer the data type of a given string
* Support for multiple data types, including numeric, categorical, and text
* Utilize a collection of pre-trained ML models

##Installation
###Clone the repository:
git clone https://github.com/myk93/string-data-type-inference.git

###Navigate to the project directory:
cd string-data-type-inference

###Create a virtual environment (optional but recommended):
python3 -m venv venv
source venv/bin/activate

###Install the required dependencies:
pip install -r requirements.txt

##Usage
Follow the example below:
in the line new_string 
'''
new_strings = ['something', '100', '2.718', 'False', '12345','1993-10-28']
'''
and then run the project

##Models
The project includes the following ML models for data type inference:
* 'linear regresion'
* 'SVC'
* 'forest'
* 'decison tree'

##Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch.
Make your changes and commit them.
Push your changes to your fork.
Submit a pull request.
Please ensure that your code adheres to the existing style and includes appropriate tests.


##Acknowledgments
This project was inspired by the need to automatically infer data types for string inputs in various applications.
If you find this project useful or have any suggestions, feel free to contribute or reach out. Happy data type inference!
