# Bungholio

Monitors Amazon and sends a message to a webhook when watched products (like TP) become available. It will send a message at most once per day per product.


**Note**

Only tested with Discord
## Installation

1. Clone this repo.
2. Modify items.json with the name and url of products you want to watch.
3. Create a .env file with your Webhook URL

```
WEBHOOK_URL=URLHERE
```

4. Run it

```
   node index.js
```
