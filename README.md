# LectureSummarizer
Takes in lecture notes [copy paste as PDF] and summarizes them, regardless of the length of the PDF. GPT has a limit, this script bypasses the limit by dividing the text into chunks and processing individual chunks before merging it as one document.

Steps:

1. Create an API key: https://platform.openai.com/account/api-keys
2. Paste your API key in "openaiapikey.txt"
3. Create an empty folder called "gpt_logs"
4. Copy your lecture notes PDF as text (CTRL+A and CTRL+C will do)
5. Open terminal, navigate to directory, and run "python3 recursively_summarize.py"

Your summarized document will be saved as a text file in this project's folder.
