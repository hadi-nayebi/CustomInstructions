# Custom Instructions for LLM Models
Consider the generative power of LLMs. After utilizing them for some time and observing their use by others, one can discern two distinct perspectives. In one, we view them simply as generative models—LLMs churning out text. This perspective undermines the importance of the input text. In contrast, another perspective shines a light on the importance of the input text that LLMs require to yield quality outputs. From this angle, LLMs act as magnifiers, a text calculator, honing in on the text we provide to enhance our desired outcomes. Here, the emphasis is on optimizing that input text. 
```
Text generation:
LLM =====> Text

Text Calculator:
             LLM
Text + Text =====> Text
```

Over the past year, the art of crafting input text has evolved. With prompt engineering and tailored instructions, the precision of input has become as pivotal as the LLM itself. We now understand an LLM’s output is only as good as its input. Even smaller models can signiicantly improve by optimizing the input.

## Introduction
Welcome to the guide on creating custom instructions for LLM models. This document will provide you with an overview of the various building blocks used in custom instructions, best practices, notations, and more. First, let's learn what a custom instruction is and does.<br>
<br>
LLMs, as the core technology using custom instructions, are, by definition, language models. This means that these models understand the structure of a language and can produce coherent text by predicting one word (~token) at a time and extending the user's prompt (message). In other words, LLMs are like text calculators and they receive a text (prompt) from the user and produce a reasonable extension of that text. The objective of custom instructions is to create consistent behavior with an LLM as such when it combined with user input, will lead to better response. The training dataset for LLM fine-tuning can produce LLMs with certain capabilities. For example, if trained on a screenplay, if the user starts with the first paragraph of a screenplay, the LLM can continue and finish the screenplay (in principle). However, if the LLMs are fine-tuned on conversational text, they will mimic conversational-style text. Many LLMs we often use are fine-tuned on instruction tasks and can follow the user's instructions to completion (in principle).<br>
<br>


## Building Blocks
coming soon!

## Best Practices
coming soon!


That's it! You now have a basic template for creating custom instructions for LLM models. Happy creating!
