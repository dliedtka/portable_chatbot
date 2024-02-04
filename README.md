# Portable ChatUI

Portable ChatUI provides a no-frills UI that allows you to interact with the OpenAI API in settings where a more portable solution is needed (say, for example, you can't install `npm`). 

For many OpenAI customers, GPT-3.5, available for free via ChatGPT, is sufficient for many tasks. GPT-4 may be needed for more complex tasks, but that need is infrequent enough that it is not cost-effective for users to pay $20 per month for access to GPT-4 via ChatGPT. Solutions like Portable ChatUI allow users to pay only for what they use (see [OpenAI API pricing](https://openai.com/pricing)).

Portable ChatUI will attempt to replicate basic ChatGPT functionality, such as saving the user's conversation history (available by manually by importing/exporting a conversation history file). Portable ChatUI will not support other paid ChatGPT features, such as image generation, multi-modal prompts, etc.

To use Portable ChatUI, you should not need to install anything. Just open [index.html](./index.html) in a web browser, provide your API key, link your Google Drive account to save your conversation history if you wish, and submit your prompt.


To-Do List

- Intergrate conversation history with Google Drive API/other file storage API for dynamic updates.
- Price calculator/estimator.
- Stream responses.
- Set other API parameters (temperature, etc.).
- Option to opt in to automatic chat naming.
