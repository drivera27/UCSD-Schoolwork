# UCSD COGS 150 - Large Language Models and Cognitive Science (SP25)
### Final Project Summary
I used Python's `transformers` library to observe how LLMs understand nuances in language such as double negatives (i.e "You don't know *anything*" vs. "You don't know *nothing*"). I created 10 minimal pairs to compare how GPT-2 would "react" to each stimuli, which is measured by the model's **surprisal**. 

<img width="208" height="139" alt="image" src="https://github.com/user-attachments/assets/721339b9-4386-49c9-8046-75554a2b38a9" />

Since LLMs are prediction models for language, surprisal can be explained as a model's lack of expectancy for a certain word or phrase; in other words, how "surprised" it is to see that word or phrase appear.
It can also be thought of as the inverse of probability.

As one might expect, GPT-2 was more "surprised" to see sentences with double negatives.

<img width="324" height="216" alt="image" src="https://github.com/user-attachments/assets/d7c2657c-3f56-487a-a377-5de8b7036559" />

The entire report, as well as all of my code, was created using Jupyter Notebook, and can be found [here](https://github.com/drivera27/UCSD-Schoolwork/blob/main/COGS150/COGS150_FinalProject.ipynb).
