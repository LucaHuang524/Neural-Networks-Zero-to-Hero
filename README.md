# Neural Networks: Zero to Hero

My notebooks for Andrej Karpathy's [Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html) lecture series. I write each one alongside the lecture, building everything from scratch, and add my own notes where something took a while to click.

```
micrograd  →  makemore (bigram, MLP, BatchNorm, backprop, WaveNet)  →  GPT  →  tokenizer
```

| # | Lecture | Notebook | Exercises |
|---|---------|----------|-----------|
| 1 | micrograd: backpropagation from scratch | [micrograd](001_micrograd/micrograd.ipynb) | |
| 2 | makemore 1: bigram language model | | |
| 3 | makemore 2: MLP | | |
| 4 | makemore 3: activations, gradients, BatchNorm | | |
| 5 | makemore 4: becoming a backprop ninja | | |
| 6 | makemore 5: WaveNet | | |
| 7 | GPT from scratch | | |
| 8 | GPT tokenizer | | |

In progress: lecture 1.

## Running the notebooks

```
pip install -r requirements.txt
jupyter notebook
```

The graph drawings in micrograd also need the Graphviz program installed (`brew install graphviz` on macOS, or from graphviz.org on Windows).

## References

- [Lecture playlist on YouTube](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)
- [karpathy/nn-zero-to-hero](https://github.com/karpathy/nn-zero-to-hero): the course's own notebooks
- [karpathy/micrograd](https://github.com/karpathy/micrograd)
- [karpathy/makemore](https://github.com/karpathy/makemore)
- [karpathy/nanoGPT](https://github.com/karpathy/nanoGPT)
- [karpathy/minbpe](https://github.com/karpathy/minbpe)

All course material is by Andrej Karpathy. The notebooks here are my own work through it.
