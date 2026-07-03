# 🎬 FramesToFables

Generate engaging stories from a sequence of images using state-of-the-art Vision-Language Models and Large Language Models.

This project explores different image captioning models and LLMs to automatically convert a set of images into coherent and creative stories.

---

## Features

- Multiple Image Captioning Models
  - BLIP
  - BLIP-2
  - GIT
  - OFA
  - InstructBLIP
  - LLaVA (optional)

- Multiple Story Generation Models
  - Llama 3
  - Mistral
  - Gemma
  - Phi
  - GPT (optional)

- Prompt Engineering Experiments

- Quantized inference for low-memory GPUs

- Caption and story comparison

- Modular pipeline

---

## Pipeline

```
Images
   │
   ▼
Image Captioning Model
   │
   ▼
Captions
   │
   ▼
Prompt Engineering
   │
   ▼
Large Language Model
   │
   ▼
Generated Story
```

---

## Repository Structure

```
FramesToFables
│
├── notebooks/
├── src/
├── outputs/
├── images/
├── docs/
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Models Used

### Image Captioning

| Model | Purpose |
|--------|----------|
| BLIP | Baseline captioning |
| BLIP-2 | Improved contextual captions |
| GIT | Vision-language transformer |
| OFA | Unified multimodal model |
| InstructBLIP | Instruction-following captions |

### Story Generation

- Llama
- Mistral
- Gemma
- Phi

---

## Installation

Clone the repository

```bash
git clone https://github.com/<username>/FramesToFables.git

cd FramesToFables
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Usage

Run the notebook

```
notebooks/FramesToFables.ipynb
```

or execute the scripts inside `src/`.

---

## Example Workflow

1. Load image sequence
2. Generate captions
3. Save captions
4. Generate stories
5. Compare outputs
6. Evaluate different models

---

## Sample Results

### Image Caption

> "A young boy walks through a forest carrying a lantern."

### Generated Story

> "As dusk settled over the forest, the boy tightened his grip on the lantern. Every step revealed another mystery hidden beneath the ancient trees..."

---

## Comparison

| Caption Model | Story Model | Quality |
|--------------|-------------|---------|
| BLIP | Mistral | ⭐⭐⭐⭐☆ |
| BLIP-2 | Llama | ⭐⭐⭐⭐⭐ |
| OFA | Gemma | ⭐⭐⭐⭐☆ |

---

## Future Improvements

- Video-to-story generation
- Automatic evaluation using CLIPScore
- Story consistency metrics
- Interactive web interface
- Fine-tuned captioning models
- RAG-based storytelling

---

## Tech Stack

- Python
- PyTorch
- HuggingFace Transformers
- BitsAndBytes
- LangChain
- Pandas
- Google Colab

---

## Author

**Ishan Trikha**

B.Tech Mechanical Engineering

Indian Institute of Technology Kanpur

---

## License

This project is licensed under the MIT License.
