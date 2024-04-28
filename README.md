
# finetuningLLMs

NLP Research Project

## Domain-Specific Performance of Sequence-to-Sequence Models in Abstractive Text Summarization

## About Project
Text summarization  is a process that involves shortening long passages into concise summaries while preserving key information. With the advent of Sequence-to-Sequence (Seq2Seq) models, the ability to generate coherent and fluent summaries has significantly improved. However, controlling specific aspects of the output, such as word limit and the amount of paraphrasing, remains a challenge. In this paper, we evaluate Seq2Seq models with output control capabilities, enabling the generation of summaries that adhere to desired constraints. 
We used two models, Gemma V2 and Bart large CNN, and assessed their performances using ROUGE scores. We trained the model on two domains: News and Law, using relevant datasets from each field. We used Rogue N and Rogue L scores which are metrics used to evaluate the performance of automatic text summarization systems. Our analysis revealed that the Bart-Large-CNN model demonstrated a consistent performance across various domains, showing competitive results in both news and legal text summarization tasks.

# Dataset :

    BillSum Processed : https://www.kaggle.com/datasets/undersc0re/billsum-processed-train/data
    CNN-DailyMail News : https://www.kaggle.com/datasets/gowrishankarp/newspaper-text-summarization-cnn-dailymail
