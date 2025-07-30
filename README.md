# Transformer for Sentiment Analysis

In this repo, We will **implement a Transformer-based model for sentiment analysis** on the IMDb movie review dataset. we will:


## 📦 Dataset

We use the **IMDb movie reviews dataset**:

- Contains 50,000 highly polar movie reviews (25,000 for training and 25,000 for testing).
- Each review is labeled as either **positive (1)** or **negative (0)**.
- we will clean the raw text, tokenize it, and build a vocabulary before training.

## 🏗️ Model Architecture

we will build a **Transformer Encoder** model that includes:

- Word Embedding Layer
- Positional Encoding Layer
- Multi-head Self-Attention Blocks
- Feedforward Layers
- Final Classification Head

## ⚙️ Training Details

- Optimizer: `Adam`
- Loss Function: `CrossEntropyLoss`
- Batch Size: `32`
- Learning Rate: `1e-3`
- Epochs: `5`

## 📝 Sample outputs
```
Example #4
────────────────────────────────────────────────────────────────────────────────
Review snippet: i recently started to watch this show in syndication and find it a bit hit and miss some episodes are silly  doug is upset about some trivialjuvenile thing and acts stupid etcstill others are quite amusing and sometimes touching these include those episodes that face up to the complexities of the ch...

True label:      positive
Predicted label: positive

Example #5
────────────────────────────────────────────────────────────────────────────────
Review snippet: how many movies are there that you can think of when you see a movie like this i cant count them but it sure seemed like the movie makers were trying to give me a hint i was reminded so often of other movies it became a big distraction one of the borrowed memorable lines came from a movie from 2003 ...

True label:      positive
Predicted label: negative
```
