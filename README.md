# RedditAnalyzer
### A simple LLM-powered tool for analyzing a subreddit's content, primarily created to quickly understand how a tech company's users interact with the company's subreddit
Powered by langchain and anthropic - swap in a subreddit of your choosing

## Quick start
```python
# clone the repo
git clone https://github.com/beep13/RedditAnalyzer.git

# navigate into the directory and create a new virtual env if needed
cd RedditAnalyzer
python -m venv venv

# install requirements
pip install -r requirements.txt

# create a minimal .env
touch .env

# and add these credentials to it
reddit_client_id={your reddit client id}
reddit_client_secret={your reddit client secret}
anthropic_api_key={your anthropic key}

# start the notebook
jupyter notebook

# swap in the subreddit you'd like to analyze as the definition of the SUBREDDIT_NAME variable
SUBREDDIT_NAME= "whatever you'd like!"

# Then, just run the notebook top to bottom and wait for the results!
```

  
