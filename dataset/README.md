# Dataset

This folder contains the one million paragraph-level QA-pairs dataset (split into Train, Dev and Test set) described in:
[Harvesting Paragraph-Level Question-Answer Pairs from Wikipedia](https://arxiv.org/pdf/1805.05942.pdf)

## Dataset Link

[https://goo.gl/a2NzZR](https://goo.gl/a2NzZR)

## Format
The data is arranged like [SQuAD](https://rajpurkar.github.io/SQuAD-explorer/):

```
file.json
├── "data"
   └── [i]
       ├── "paragraphs"
       │   └── [j]
       │       ├── "context": "paragraph text"
       │       └── "qas"
       │           └── [k]
       │               ├── "answers"
       │               │   └── [l]
       │               │       ├── "answer_start": N
       │               │       └── "text": "answer"
       │               ├── "id": "<uuid>"
       │               └── "question": "paragraph question?"
       └── "title": "document id"
```

<!--- ## Performance
The Table below shows the neural machine reading system ([DocReader](https://github.com/facebookresearch/DrQA/tree/master/scripts/reader))'s performance on our corpus.

<p align="left"><img width="50%" src="img/performance2.png" /></p>
-->


