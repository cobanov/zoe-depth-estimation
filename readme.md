# Image Similarity Calculator

This project provides a simple image similarity calculator using the CLIP (Contrastive Language-Image Pre-training) model. It consists of two Python scripts, `predictor.py` and `app.py`, that allow you to calculate the cosine similarity between two images.

## Requirements

- Python 3.7+
- PyTorch
- FastAPI (for running app.py)

## Getting Started

1. Clone this repository to your local machine:

```bash
git clone https://github.com/cobanov/zoe-depth-estimation
cd zoe-depth-estimation
```

2. API Key to  `.env` file

```
echo IMG_API_KEY='YOUR-API-KEY' > .env
```

2. Build and run the docker image

```bash
docker build -t depth_estimation .
docker run -d -p 8003:8003 depth_estimation
```
