# The Daily 🕸 Bugle

I'm building a comic nerd app that answers my nerdy questions about superheroes. This keeps track of all the superhero stuff going on in the world. You can ask trivia things including coolest easter eggs.

![image](https://github.com/user-attachments/assets/a15f54ba-14f3-498d-8de6-2d74f3856d1c)

My project map:
- Collect data
- Fine-tune an open source llm
- Vector db
- Query the system with prompts
- Create a simple ui

## Index

1. Data collection
2. Feature engineering
3. Training
4. Inference
5. Monitoring
6. UI

## Setup

### Environment

I am using `conda` for creating environments.

```bash
conda create -n comicapp python=3.11

conda activate comicapp
```

I am using `poetry` for package management. I will use `uv` in prod as it is very fast.

```
cd comicapp

poetry init

poetry add numpy
```

## Data Collection Pipeline

Once the data is scraped, I'm cleaning and storing it in a nosql database.

I am scraping 
