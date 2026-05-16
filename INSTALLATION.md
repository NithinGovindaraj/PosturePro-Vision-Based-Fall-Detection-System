# Installation Guide

## Requirements 
- Python 3.9
- 32GB microSD card (with Raspberry Pi OS installed)

## Setup

### 1. Clone Repository
```bash
git clone https://github.com/yourusername/PosturePro.git
cd PosturePro
```

### 2. Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Vosk Model Setup
```bash
cd models/
wget https://alphacephei.com/vosk/models/vosk-model-small-en-us-0.15.zip
unzip vosk-model-small-en-us-0.15.zip
cd ..
```

### 5. Run
```bash
python main.py
```
