# The Daily 🕸 Bugle

I'm building a comic nerd app that answers my nerdy questions about superheroes. This keeps track of all the superhero stuff going on in the world. You can ask trivia things including coolest easter eggs.

![image](https://github.com/user-attachments/assets/a15f54ba-14f3-498d-8de6-2d74f3856d1c)

My project map:
- collect data
- fine-tune an open source llm
- vector db
- query the system with prompts
- create a simple ui

1. Data collection
2. Feature engineering
3. Training
4. Inference
5. Monitoring
6. UI

## Dataset

Let's create a synthetic instruction-following dataset 
[Alpaca](https://crfm.stanford.edu/2023/03/13/alpaca.html)

## Data Collectionn Pipeline

Once the data is scraped, I'm cleaning and storing it in a nosql database. I have a change data capture pattern implemented that checks any change made in the database.
