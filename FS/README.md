# AI File Management System

An intelligent file management system with:
- Local LLM tagging
- Semantic search using embeddings
- SQLite indexing
- Background multiprocessing workers

## Features
- Automatic tag generation
- Semantic similarity search
- File indexing
- Local Llama model integration
- all file management methods
- hash changes detection

## SetUp
- make model folder 
- put model on model folder
model/
    all-MiniLM-L6-v2/
    qwen2.5-1.5b-instruct-q8_0.gguf
    llama-2-7b-chat.Q4_K_M.gguf

## Run 
- run watcher/watcher_service.py run seperate (work as backgorund service)
- in main run api.py

## Installation

```bash
pip install -r requirements.txt```

