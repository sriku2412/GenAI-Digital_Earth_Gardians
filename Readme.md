**README.md**

# Circular Economy Solution Evaluator

**Overview**

This project implements a Python application that utilizes the OpenAI API to evaluate solutions related to the circular economy. The application assesses solutions based on their novelty, utility, and surprise elements.

**Installation**

* Ensure you have Python 3.10 installed on your system.
* Clone the repository:
```bash
git clone https://github.com/sriku2412/GenAI-Digital_Earth_Gardians.git
cd GenAI-Digital_Earth_Gardians
```
* Install dependencies:
```bash
pip install --upgrade typing_extensions
pip install --upgrade pydantic
pip install --upgrade gradio
pip install openai==0.28
pip install scikit-learn
pip install huggingface_hub
```

**Set Up OpenAI API Key**

Replace `INSERT YOUR API KEY HERE` with your actual OpenAI API key in the code.

**Usage**

1. Navigate to the project directory:
```bash
cd GenAI-Digital_Earth_Gardians
```
2. Execute the main script:
```bash
GenAI_model_digital_Earth_Guardian.ipynb
```

The application will launch a Gradio interface at the following URL:
```
localhost:8000
```

**Features**

* Solution Evaluation: Evaluates solutions based on their novelty, utility, and surprise elements.
* Gradio Web Interface: Provides an easy-to-use web interface for interacting with the model.
* OpenAI Integration: Leverages the OpenAI API for generating evaluations of the solutions.

**Contributing**

Contributions are welcome! Please fork the repository, submit a pull request with your changes, and follow the project's contributing guidelines.

**License**

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.
