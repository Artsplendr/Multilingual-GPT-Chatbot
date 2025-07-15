# Multilingual Chatbot with OpenAI GPT & Google Translate

A lightweight, zero-cost prototype that chats in English 🇬🇧 and German 🇩🇪 (extendable to 130+ languages) by combining the power of OpenAI’s GPT models with free Google Translate service via deep-translator.

## Features

- Automatic language detection:	uses langdetect to identify the user’s language (any script).
- Bi-directional translation:	routes non-English input through Google Translate, sends the English text to GPT, then returns GPT’s answer translated back to the original language.
- GPT integration: defaults to gpt-3.5-turbo.
- 100 % free translation:	relies on Google Translate’s public endpoints via deep-translator, no Google Cloud key needed.



