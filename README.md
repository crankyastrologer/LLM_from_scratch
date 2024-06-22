# LLM From Scratch

This project is basically an LLM designed and trained from scratch inspired by the paper [Attention is all you need](https://arxiv.org/pdf/1706.03762.pdf) and gpt architechture
<br>
It is trained using [open webtext corpus](https://skylion007.github.io/OpenWebTextCorpus/)
<br>
This is just supposed to be proof of concept and an exercise in designing, training and deploying a chatbot.
<br>
Feel free to use this for your own projects
## Tech used
- [Pytorch directml](https://pypi.org/project/torch-directml/): I have and AMD GPU so to I prefer this to take 
advantage of it even though some functions still fall back to CPU it still accelerated training exponentially.
- [tqdm](https://pypi.org/project/torch-directml/): For showing progress bars
- [Concurrent.futures](https://docs.python.org/3/library/concurrent.futures.html#module-concurrent.futures): For accelerating 
data preprocessing

