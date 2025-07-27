## Tokenization
To get an intuition for how tokenization works, use the [OpenAI Tokenizer](https://platform.openai.com/tokenizer) to see how tokens look. Try out a few prompts - and see how that gets converted into tokens, paying attention to how whitespace characters and punctuation marks are handled. 

### Prompt 1
**Prompt:** The quick brown fox jumps over the lazy dog.

**Reflection:**  
When I tested this sentence in the OpenAI Tokenizer, I noticed that each word is treated as a separate token, like "The", "quick", "brown", etc. The period at the end is also its own token. Spaces between words are not shown as individual tokens, but they are considered in the total count. It was interesting to see how efficiently the tokenizer splits natural language.

---

### Prompt 2
**Prompt:** Hello, world! How's everything?

**Reflection:**  
This prompt showed that punctuation marks like commas, apostrophes, and exclamation points are treated separately. For example, "Hello" and the comma are different tokens, and "How’s" may be split into "How" and "’s". This helped me understand how even small symbols can change the number and type of tokens generated.


Next we'll learn about [Prompt Engineering]((../lesson-1.2/writing-prompts.md)
