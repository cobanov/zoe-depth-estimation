# Depth Estimation

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
