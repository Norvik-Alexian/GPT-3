# GPT-3

GPT-3 models can understand and generate natural language. Four main models with different levels of power suitable for different tasks. Davinci is the most capable model, and Ada is the fastest.

## Engines
### text-davinci-002:
Most capable GPT-3 model. Can do any task the other models can do, often with less context. In addition to responding to prompts, also supports inserting completions within text. Max tokens request for Davinci engine is 4,000 tokens.

### text-curie-001:
Very capable, but faster and lower cost than Davinci. Max tokens request for Curie engine is 2,048 tokens.

### text-babbage-001:
Capable of straightforward tasks, very fast, and lower cost. Max tokens request for Babbage engine is 2,048 tokens.

### text-ada-001:
Capable of very simple tasks, usually the fastest model in the GPT-3 series, and lowest cost. Max request for Ada engine is 2,048 tokens.

## Tokens
Models understand and process text by breaking it down into tokens. Tokens can be words or just chunks of characters. For example, the word “hamburger” gets broken up into the tokens “ham”, “bur” and “ger”, while a short and common word like “pear” is a single token. Many tokens start with a whitespace, for example “ hello” and “ bye”.

The number of tokens processed in a given API request depends on the length of both your inputs and outputs. As a rough rule of thumb, 1 token is approximately 4 characters or 0.75 words for English text. One limitation to keep in mind is that your text prompt and generated completion combined must be no more than the model's maximum context length.