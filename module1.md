---
layout: page
title: "Module 1: Unraveling the Mechanics of AI"
---

# Module 1: Unraveling the Mechanics of AI

> A Beginner's Guide to AI: Discussing LLMs and Foundational Structures
> 

### **Understanding Artificial Intelligence**

Artificial Intelligence (AI) delves into the realm of computer science with the aim of mimicking aspects of human intellect. This includes capabilities such as learning, deciphering patterns, problem-solving, and comprehending language. Today, we encounter AI functionalities in numerous everyday tools like smart voice assistants, tailored content suggestions, and self-driving vehicles.

In recent times, the emergence of Large Language Models (LLMs) by entities such as OpenAI, Anthropic, and Baidu, exemplified by tools like ChatGPT, has brought AI-driven chat interfaces to the forefront for everyday users.

### **What Exactly is an AI Model?**

![Untitled](LLM101%200df2aeaf17bd4854b0956e0cbebe412c/Untitled.png)

An AI model can be visualized as a mathematical analogy of processes we observe in the real world. To exemplify, models dedicated to language are designed to produce text that mimics human communication, dependent on the input they receive. There are also other models that specialize in dealing with various tasks, such as video processing, image generating, playing chess, etc.

### **Delving into the World of Large Language Models (LLMs)**

LLMs, exemplified by creations like OpenAI's GPT-4, stand as a distinct category of AI models. Their primary function? Utilizing machine learning techniques to craft text that mirrors human communication. Though they're trained using an array of online text sources, they remain unaware of the specific content in their training set and cannot tap into private or classified data unless it's directly shared during an interaction.

![Untitled](LLM101%200df2aeaf17bd4854b0956e0cbebe412c/Untitled%201.png)

### **How LLMs Works?**

At their core, LLMs operate by estimating the likelihood of a subsequent word (or "token" as we'll dive into later) relying on prior words in a statement.

For example:

![Untitled](LLM101%200df2aeaf17bd4854b0956e0cbebe412c/Untitled%202.png)

The LLM will calculate the likelihood of these words and output the most possible one, like books.

This mechanism ensures the production of contextually relevant and fluent sentences. Nonetheless, it's pivotal to understand that, unlike humans, LLMs lack genuine comprehension of content and don't possess the ability to think or be aware autonomously.

In our case, SmartPrep's foundation models are tailored for dealing with educational tasks and aligned with educators' and students' needs.

### What are tokens and how are they used?

In language models such as ChatGPT, the term "token" refers to the smallest unit of text that the AI model can comprehend and handle. Tokens can range from single characters, like 'a', to complete words, like 'apple'. Tokens can be thought of as the fundamental components of a conversation, similar to how individual Lego bricks make up a Lego structure. Every conversation or text is composed of these individual tokens.

![Untitled](LLM101%200df2aeaf17bd4854b0956e0cbebe412c/Untitled%203.png)

Large Language Models (LLMs) such as ChatGPT read and produce text by processing one token at a time. For example, when given a prompt, the AI reads it token by token and generates a response accordingly. LLMs also have a maximum token limit for processing, with GPT-3 having a limit of 2048 tokens.

The number of tokens in a conversation, including the prompt and the AI-generated response, is crucial for an LLM like ChatGPT. It affects everything the model does, from understanding the prompt to generating a response. It is important to stay within the model's token limit. To give you an idea of scale, GPT-3 has a context window of 2048 tokens, which is roughly equivalent to 3-4 pages of a typical book. In contrast, a novel like "The Great Gatsby" has around 50,000 words, which exceeds the model's context window.

### What are ****Context Windows?****

The context window, in the realm of language models like ChatGPT, refers to the recent conversation history that the model considers when generating a response. It includes both the model's own messages and the user's messages, and its size is measured in 'tokens'.

The size of the context window is determined by the model's architecture. For example, GPT-3 has a maximum token limit of 2048 tokens. This means that it can consider the last 2048 tokens of text as its context. If a conversation exceeds this limit, the model cannot see or consider text beyond it.

![Untitled](LLM101%200df2aeaf17bd4854b0956e0cbebe412c/Untitled%204.png)

In a chat application, the context window affects how the AI responds to user inputs. If a conversation becomes long enough to exceed the model's context window, the AI may lose track of the context and start responding inappropriately or inconsistently.

For instance, if you ask the AI to remember something at the beginning of a long conversation and then refer back to it after multiple exchanges, the AI might not remember the initial information if it's outside of its context window.

There are multiple strategies available to overcome the limitations of the context window. One method involves carefully managing the conversation to ensure that the most important information remains within the model's context window. Another approach is for developers to explicitly provide relevant past information when it becomes necessary.

### **LLMs In The Future**

Though LLMs stand for Large Language Models now, they are iterating very quickly and have started to gain abilities other than purely generating text. For example, a majority of AI companies are working on multimodal models, which can be used to process data other than text forms like images, audio, video, etc. One thing to keep in mind is that though LLMs have great comprehension and inference abilities, there is no evidence till now to show that LLMs are self-aware.

### **Conclusion**

In wrapping up the inaugural module of your instructional journey, we've navigated through AI's rudimentary concepts, clarified the nature of an AI model, ventured into the intricacies of Large Language Models (LLMs), and underscored the critical role of foundational models. 

### **Key Takeaways**

1. **AI Fundamentals**: AI aims to replicate aspects of human intelligence such as learning, recognizing patterns, solving problems, and understanding language. Its applications are widespread in tools like voice assistants, recommendation systems, and self-driving cars.
2. **Rise of Large Language Models (LLMs)**: LLMs, developed by entities like OpenAI, Anthropic, and Baidu, and exemplified by ChatGPT, have become prominent in providing AI-driven chat interfaces for everyday use.
3. **AI Models Explained**: AI models are mathematical analogies of real-world processes. Language models, for instance, generate text that resembles human conversation based on input.
4. **Understanding LLMs**: LLMs like GPT-4 use machine learning to produce human-like text. They are trained on diverse online text sources but do not access private or classified information unless explicitly provided during interactions.
5. **How LLMs Work**: LLMs predict the likelihood of the next word in a sentence based on previous words, generating contextually relevant text. However, they lack genuine understanding or autonomous thinking.
6. **Tokens in AI Models**: Tokens are the smallest units of text in AI models like ChatGPT, ranging from single characters to whole words. They are the building blocks of conversations, and LLMs process text one token at a time.
7. **Context Windows in LLMs**: The context window is the recent conversation history that the model considers while responding. Its size is limited by the model's architecture, affecting the AI's response accuracy in prolonged conversations.
8. **Advancements and Future of LLMs**: LLMs are rapidly evolving beyond text generation. Multimodal models are being developed to process non-textual data like images and audio. However, there is no evidence of self-awareness in LLMs.