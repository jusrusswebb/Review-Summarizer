# Amazon-Review-Summarizer

This Python script utilizes Selenium for web scraping to collect Amazon product reviews and OpenAI's GPT-3.5 for natural language processing to summarize the gathered reviews. The process involves fetching reviews from multiple pages of a specified product on Amazon and then summarizing the common sentiments including complaints.

## Installation 

Install [Langchain](https://github.com/langchain-ai/langchain) and other required packages 

Modify `constants.py.default` to use your own [OpenAI API key](https://platform.openai.com/account/api-keys), and rename it to `constants.py`.

## Example usage 

Run summaryGUI.py 

`python3 summaryGUI.py`

Input a URL from any Amazon product 

<img width="485" alt="guipic" src="https://github.com/jusrusswebb/review-summarizer/assets/122849382/544fff56-227e-4c04-ba8b-a31c4d4899f4">








