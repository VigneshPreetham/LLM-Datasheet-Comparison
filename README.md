# LLM Datasheet Comparison


## What this is?
- This project allows users to ask various questions comparing specifications of different mobile phones
- Allows the user to decide which phone to buy: which company, low-tier, mid-tier, or flagship based on their needs


## How this is done?
- Used quantized LLM (Llama 3-8B) to answer questions with RAG
- This uses different chunk sizes for the various specification documents and multi-layer ChromaDB querying to boost retrieval accuracy
