**EthioMart Amharic Named Entity Recognition (NER) System**

**Project Overview**

EthioMart aims to centralize e-commerce activities from various Ethiopian-based Telegram channels, enabling real-time data extraction to create a unified platform. This project focuses on:

	. Extracting real-time data (text, images, documents) from Telegram channels such as @ZemenExpress ,@nevacomputer ,@helloomarketethiopia,forfreemarket, Shewabrand,
	
	. Fine-tuning a large language model (LLM) for Amharic Named Entity Recognition (NER).
	
	. Identifying key entities such as products, prices, and locations in Amharic text.

**Folder Structure**

REALtIME-DATA-EXTRACTION-FROM-TELEGRAM-CHANNEL-WORKFLOW/ ├── . notebooks/ | ├── Amharic_E-Commerce_Data_scrapping.ipynb │ ├── Data_preprocessing_and_CoNLL.ipynb │ └── README.md ├── . scripts/ ├── . src/ ├── .tests/ ├── .gitignore ├── README.md └── requirements.txt

**Features**

Real-Time Data Ingestion : A custom scraper that connects to Telegram channels and fetches messages, images, and metadata.
Text Preprocessing : Tokenization, normalization, and handling Amharic-specific linguistic features.
