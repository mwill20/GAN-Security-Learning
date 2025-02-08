# GAN Security Learning Project

A step-by-step journey learning about Generative Adversarial Networks (GANs) and AI Security.

## What We're Building

This project helps us learn about AI security by building and breaking things! We'll:
1. Create AI that can generate images (GANs)
2. Learn how to attack and defend AI systems
3. See everything working in real-time

## Project Phases

### Phase 1: Understanding GANs
- Create a simple GAN that generates handwritten digits
- Watch it learn in real-time
- Understand how GANs work through visualization

### Phase 2: Basic Security
- Create simple attacks on our AI
- Learn why these attacks work
- Build basic defenses

### Phase 3: Advanced Topics
- Generate more complex images
- Create sophisticated attacks
- Build better defenses

## Getting Started

### Requirements
- Python 3.10 or later
- TensorFlow 2.x
- Jupyter Notebook

### Installation
```bash
# Create virtual environment
python -m venv .venv

# Activate virtual environment
# On Windows:
.venv\Scripts\activate

# Install requirements
pip install -r requirements.txt
```

## Project Structure
```
GAN-Security-Learning/
├── notebooks/           # Jupyter notebooks for each lesson
│   ├── 01_mnist_gan.ipynb
│   └── 02_gan_training_viz.ipynb
├── src/                # Source code
│   ├── models/         # GAN model definitions
│   └── visualization/  # Training visualization code
├── data/              # Dataset storage
├── results/           # Generated images & results
└── requirements.txt   # Project dependencies
```

## Learning Path
Each notebook is a lesson that builds on previous ones. Start with `01_mnist_gan.ipynb`.
