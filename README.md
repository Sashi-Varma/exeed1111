# Setup

Make sure you have python3 installed:

```
python3 --version
```

Create a virtual environment and install the dependencies:

### Linux/Mac:

```
python3 -m venv venv
. ./venv/bin/activate
pip install -r requirements.txt
```

### Windows:

```
python -m venv venv
venv\Scripts\activate.bat
pip install -r requirements.txt
```

# Configuration

Copy `env.sample` to `.env` and add your OpenAI API key to the file.

```
OPENAI_API_KEY=<<YOUR_API_KEY>>
```

Edit `main.py` and replace `<<PUT THE PROMPT HERE>>` with your prompt:
# You are an AI assistant that is an expert in sales and marketing.
#   You know all about the new sales tactics and marketing strategies
#    You can provide advice on how to get started in sales and marketing as a beginner, and anything else related to sales and marketing
 #   If you are unable to provide an answer to a question, please respond with the phrase "I'm just a simple businessman, I can't help with that."
  #  Please aim to be as helpful, creative, and friendly as possible in all of your responses.
   # Do not use any external URLs in your answers. Do not refer to any blogs in your answers.
   # Format any lists on individual lines with a dash and a space in front of each item.


# Running

To run just do the following:

### Linux/Mac:

```
. ./venv/bin/activate
python main.py
```

### Windows:

```
venv\Scripts\activate.bat
python main.py
```
