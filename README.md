# Word2Vec Workshop - Inside Word Embeddings

**You must give credit to Ananda Rimal if you use these slides. Credit is required.**
Licensed under CC BY 4.0 - https://creativecommons.org/licenses/by/4.0/

---

Workshop resources by Ananda Rimal, AI Researcher and ML Instructor

A deep dive into the real mathematical training process behind the classic Google / Mikolov Word2Vec approach.

---

## About This Repository

This repository contains all workshop materials, slides, code, and supporting resources for understanding Word2Vec from the ground up.

Rather than treating Word2Vec as a black box, this workshop unpacks every step of the actual training loop: how the model sees context, how it calculates loss, and how it updates weights through backpropagation. If you have ever wondered what is really happening inside Word2Vec, this is the answer.

---

## Topics Covered

| Topic | Description |
|---|---|
| CBOW | Continuous Bag-of-Words, predicting a target word from its context |
| Skip-gram | Predicting surrounding context words from a single target word |
| Word Embeddings | What embeddings are, why they encode meaning, and how they emerge from training |
| Negative Sampling | The trick that makes training tractable at scale |
| Sigmoid Activation | How the output probability is computed |
| Loss Function | Binary cross-entropy loss and why it is used |
| Weight Updates | Gradient descent and backpropagation through the embedding matrices |

---

## Repository Structure

`
Word2VecLab-Inside-Word-Embeddings/
    resources/
        word2vec by ananda rimal.pptx   (Workshop slide deck, CC BY 4.0)
    code/                               (Code examples and notebooks, MIT License)
    README.md
`

---

## Workshop Slides

**You must give credit to Ananda Rimal if you use these slides. Credit is required.**

The slide deck (resources/word2vec by ananda rimal.pptx) walks through the intuition behind distributed word representations, step-by-step CBOW and Skip-gram architectures, the full forward pass with loss computation and weight update cycle, negative sampling in detail, and visual examples of learned embedding spaces.

License: Slides and all educational content are released under CC BY 4.0. You are free to use, share, adapt, and build upon this material for any purpose, including commercially, as long as you give appropriate credit.

### Required Attribution

When using or referencing these slides or any educational content from this workshop, you must include the following credit:

```
Word2Vec Workshop Resources by Ananda Rimal | AI Researcher and ML Instructor
Licensed under CC BY 4.0 - https://creativecommons.org/licenses/by/4.0/
```

Anyone can use these slides, but credit to Ananda Rimal is required.

---

## Code

All code in the code/ directory is released under the MIT License, free to use, modify, and distribute with or without attribution (though it is appreciated).

---

## License Summary

| Content Type | License |
|---|---|
| Code (.py, notebooks, scripts) | MIT License (https://opensource.org/licenses/MIT) |
| Slides, diagrams, written explanations | CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/) |

---

## Author

Ananda Rimal
AI Researcher and ML Instructor

If you find this useful, feel free to share it. Just remember to give credit.
