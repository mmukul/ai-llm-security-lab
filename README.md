# AI LLM Security Lab 🔐

Hands-on demos for LLM security based on OWASP LLM Top 10.

## Setup

Install Ollama:
https://ollama.com

## Build Models

ollama create securebot -f modelfiles/Modelfile.securebot  
ollama create vulnerablebot -f modelfiles/Modelfile.vulnerablebot  
ollama create debugbot -f modelfiles/Modelfile.debugbot  

## ▶️ Run

ollama run debugbot  

## Test via Python

pip install -r requirements.txt  
python scripts/test_debugbot.py  

## Purpose

- Demonstrate prompt injection  
- Compare secure vs vulnerable models  
- Build LLM security awareness  

## YouTube Series

LLM Security Mastery 🔐