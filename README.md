# Reinforcement Learning for Mario Game
![Mario_Thumbnail](https://github.com/CodeWithCharan/Super-Mario-AI/assets/106027109/5a0cdf8a-c826-4921-a865-6940d0b113b0)

## Overview

In this project, I've developed an AI model using Reinforcement Learning that can play the Super Mario game. The project is documented step-by-step in the [AI_model.ipynb](https://github.com/CodeWithCharan/Super-Mario-AI/blob/main/AI_model.ipynb) file, covering the following sections:

1. Setup Mario Environment
2. Preprocess Environment
3. Train the RL Model
4. Test it Out

## Requirements

To run this project, you will need the following software and libraries:

- Python 3
- OpenAI Gym/Gymnasium
- PyTorch
- Stable-Baselines3

## Setup Instructions

Follow these steps to set up and run the project:

1. Clone the repository:

    ```
    git clone https://github.com/your-username/Super-Mario-AI.git
    cd Super-Mario-AI
    ```

2. Download Python 3.11.2 from [here](https://www.python.org/downloads/release/python-3112/)

3. Create a virtual environment for the specific Python version:

    ```
    virtualenv -p <paste_python_3.11.2_path_location> marioenv
    ```

4. Activate the virtual environment:

    - In Command Prompt (CMD):

        ```
        marioenv\Scripts\activate.bat
        ```

    - In PowerShell:

        ```
        marioenv\Scripts\Activate.ps1
        ```

5. Install the project dependencies:

    ```
    pip install -r requirements.txt
    ```

6. Setup Jupyter Notebook for the virtual environment:
   
    - Install Jupyter Notebook (ignore if you already have it):
      
      ```
      pip install notebook
      ```
      
    - Install IPykernel
      
      ```
      pip install ipykernel
      ```
      
    - Register the virtual environment with Jupyter

      ```
      python -m ipykernel install --user --name=marioenv
      ```
      
    - Start Jupyter Notebook:

      ```
      jupyter notebook
      ```
      
    - In Jupyter Notebook, select "Kernel" > "Change Kernel" and choose "marioenv" to use the virtual environment.


7. Follow the instructions in [AI_model.ipynb](https://github.com/CodeWithCharan/Super-Mario-AI/blob/main/AI_model.ipynb) file to train and test out the AI model's performance in the Super Mario game.