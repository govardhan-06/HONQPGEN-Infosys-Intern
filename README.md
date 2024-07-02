# HoNQP-Gen AI Tool
(Infosys Springboard Internship Project)

## Project Aim

The primary goal of the HoNQP-Gen AI Tool is to develop an advanced system capable of generating high-quality, hands-on Java programming question papers. The system is trained on a carefully curated dataset of Java code problems and solutions to ensure the production of relevant and educational questions.

## Goal

This project aims to streamline the creation of educational content by providing educators with a powerful tool to enhance learning experiences in computer science. By leveraging advanced models such as the Mistral-8x7b, the system can produce contextually appropriate and high-quality questions.
## Key Features

- **Code Generation:** Automatically generate Java code questions and solutions.
- **Class Diagram Creation:** Create relevant class diagrams to complement the generated questions.
- **Document Generation:** Generate comprehensive documents including questions, solutions, and diagrams.

## Installation

To get started with the project, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/govardhan-06/HONQPGEN-Infosys-Intern.git
   cd HONQPGEN-Infosys-Intern
   ```

2. **Create a virtual environment (optional but recommended):**

   ```bash
   # If using virtualenv
   virtualenv venv
   source venv/bin/activate

   # If using venv (Python 3 standard library)
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables:**

   Create a `.env` file in the root of your project with the following content:

   ```
   GEMINI_API_KEY="<GEMINI API KEY>"
   GROQ_API_KEY="<GROQ API KEY>"

   ```

## Usage

Describe how to use the project. Include any additional steps or configurations if necessary.

1. **Start Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

   This will open Jupyter Notebook in your web browser.

2. **Open the notebook:**

   Navigate to the `.ipynb` file you want to work on and click to open.

3. **Run the notebook:**

   Execute the cells in the notebook to see the output.

## Configuration

Explain any additional configuration or setup required for the project, if applicable.

- **File Structure:**

  ```
  /
  ├── .gitignore
  ├── .env
  ├── model.ipynb
  ├── gemini.ipynb
  └── requirements.txt
  ```

- **Environment Variables:**

  Ensure that all necessary environment variables are set in the `.env` file before running the project.

