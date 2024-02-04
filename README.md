# Rails Issues Analysis

Description
---
This repository provides some basic analysis of the issues of the [Ruby on Rail](https://github.com/rails) repository: [rails/rails](https://github.com/rails/rails/). The repository tries to answer the following questions: 
- How do the number of issues evolve over time?
- Are there any periods in which we get more issues?
- Is there anyone who reports more issues than others?
- What is the most popular category (label)?
- Performing basic modeling (pre-trained from Huggingface) to predict the labels for the issues using their description.

Setup
---
- Install all the dependencies
  - First, install the torch and cudatoolkit using the below script
    - For Windows
     ```bash
     pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
    ```
     
     - For Linux /Mac
    ```bash
      pip3 install torch torchvision torchaudio
    ```
     
  - Then, Install the other requirements, using the below script
  ```bash
  pip install requriements.txt
  ```
- create an `env.json` file in the directory and store the username and password, such as shown as:
  ```bash
  {
    "username": "YOUR_USERNAME",
    "password": "YOUR_PASSWORD"
  }
  ```
Code Execution
---
Now, everything is ready, execute the code in the Jupyter Notebook file, `rails_issues_analysis.ipynb`
