# Reate Download Automation

<a href="https://www.linkedin.com/in/rafael-goto-6027a8206/"><img src="https://img.shields.io/badge/-Let's%20Connect-blue"></a>
<a href="https://reate.cprm.gov.br/anp/TERRESTRE"><img src="https://img.shields.io/badge/-REATE%20repository-8A2BE2"></a>

Welcome! In this repository you will find the code for the automation of the download of petroleum well files using Selenium, streamlining data collection from the [REATE repository](https://reate.cprm.gov.br/anp/TERRESTRE) of Brazilian terrestrial sedimentary basins containing over 40 terabytes of data. 

<br> 

## Table of Contents

- [Prerequisites](#prerequisites)
- [Setting Up the Environment](#setting-up-the-environment)
- [Installing Dependencies](#installing-dependencies)
- [Your First Automation](#your-first-automation)

## Prerequisites

To work on this project, ensure you have the following installed:
- Python 3.10 or above (3.12 recommended)
- Git (for cloning the repository)
- Chrome Driver (download [here](https://googlechromelabs.github.io/chrome-for-testing/))

## Setting Up the Environment

1. Clone the repository:
    ```bash
    git clone https://github.com/rafaseto/reate-bot.git
    cd reate-bot
    ```

2. Create a virtual environment in the project directory:
    ```bash
    python -m venv .venv
    ```

3. Activate the virtual environment:
   - On Windows:
     ```bash
     .venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source .venv/bin/activate
     ```

## Installing Dependencies

With the virtual environment activated, install the required packages:

```bash
pip install -r requirements.txt
```

## Your First Automation

To get started right away, I set up a `test_file.txt` with the paths of some well files to download as an example.

1. Open the `src/app.py` file and insert your `chromedriver.exe` path in line 12.

2. Change the directory to `src`
    ```bash
    cd src
    ```  

3. Run 
    ```bash
    python app.py
    ``` 
