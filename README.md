# eatright

> [!NOTE]
> This is just an idea. I'm here to show how we can build LLMOps capability. So I do not consider building perfect datasets, building eval systems or improving accuracy to near 100%.

I'm building an health expert powered by an LLM. It listens to health related websites like men's health (only atm). Builds the real-time knowledge. Fine-tunes the LLM. Creates an inference service.

## Dataset

Let's create a synthetic instruction-following dataset 
[Alpaca](https://crfm.stanford.edu/2023/03/13/alpaca.html)

## Data extraction

Once the data is scraped, I'm cleaning and storing it in a nosql database. I have a change data capture pattern implemented that checks any change made in the database.
