# The Daily 🕸 Bugle

I'm building a comic nerd app that answers my nerdy questions about superheroes. This keeps track of all the superhero stuff going on in the world. You can ask trivia things including coolest easter eggs.

![image](https://github.com/user-attachments/assets/a15f54ba-14f3-498d-8de6-2d74f3856d1c)

My project map:
- ~Setup and installations~
- Collect data
- Fine-tune an open source llm
- Vector db
- Query the system with prompts
- Create a simple ui

## Index

1. Data Collection
2. Feature Engineering
3. Training/Finetuning a LLM
4. Inference Service
5. Monitoring
6. UI/UX

## Setup

### Environment

I am using `conda` for creating environments.

```bash
conda create -n comic python=3.11

conda activate comic
```

I am using `poetry` for package management. I will use `uv` in production because its very fast.

```
cd comic

poetry init

poetry add numpy pandas
```

### Task Runner

Instead of using `Makefile` for simple automation, i'm using [poe the poet](https://github.com/nat-n/poethepoet) plugin. I can just add the scripts in the `pyproject.toml` file and execute them. It works well with poetry.

## Data Collection Pipeline
 
