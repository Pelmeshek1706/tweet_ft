# Fine-Tuning model for generating text (seq2seq task)

# Main purpose - **Generating humanable text** for X(Tweeter) 

In the end you should generate tensor of random numbers, model take these numbers and generate tweets.

- parsing_twitter.ipynb:
    - Include 2-ways scraping : from your <code>.json</code> files(warmscraping) or from X(Twitter) from your own usernames(cold scraping).
    - Basic preprocessing: Removing link, smiles and short texts(size depends from your choise. In my case **limit = 10** token(for flan-t5) ) 


-------------------------------
TODO:
    1. Fine-tuning preparetion
    2. Fine-tuning model + evaluation
    3. *maybe something else*
