# ESG-senti-meter
Does a wave of negative news about a company's environmental impact (e.g., “oil spill,” “pollution lawsuit”) have a stronger impact on its stock price than on its financial results?

## Description

This application take news from GNews API and analyse how they impact company's stock especially due to environments news.

---

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing.

### Prerequisites

You will need the following tools installed on your system:
* [Python 3.8+](https://www.python.org/downloads/)
* [Git](https://git-scm.com/downloads/)
* `pip` (usually comes with Python)

### 1. Clone the Repository

First, clone this repository to your local machine:

```bash
git clone [https://github.com/](https://github.com/)pierrerenaudot/ESG-senti-meter.git
cd [ESG-senti-meter]
```

### 2. Create and Activate a Virtual Environment

```bash
# Create the virtual environment (e.g., named 'venv')
python -m venv venv

# Activate the environment
# On Windows (CMD/PowerShell):
.\venv\Scripts\activate

# On macOS/Linux (Bash/Zsh):
source venv/bin/activate
```
You will know the environment is active when you see (venv) at the beginning of your terminal prompt.


### 3. Install Dependencies

Install all the required Python packages using the requirements.txt file.

```bash
# Make sure your virtual environment is activated first!
pip install -r requirements.txt
```

### 4. Create .env file 

add GNEWS_API_KEY in it

### 💻 How to Run the Project

With your virtual environment still active, start the Jupyter Notebook server:

```bash
jupyter notebook
```
