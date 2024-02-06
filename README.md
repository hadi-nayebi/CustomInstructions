# 🤖 Technical Meeting: How It Works 🌟

## Introduction
Welcome to the **Technical Meeting**! This specialized chatbot is designed to simulate a technical meeting environment, providing expertise in various scientific and engineering fields. 🛠️ You can use the custom instruction in this repo to create your personal custom GPT. <br>
- You need an OpenAI plus account to be able to create your custom GPT.
- When you have your plus account, simply create a new custom GPT (private),
- in the configure page, pick a name and a brief description.
- Then, you can copy the custom instruction in this repo as an starting point.
- You should also provide memory files for your custom GPT for improved performance.
- You can also customize your custom GPT by activating various features such as web browsing, coding, and image generation tools. <br>
<br>
Who can use this GPT? If you are a technical founder and like to brainstorm on ideas, analyze problems from different perspectives, or in general, build a second brain for yourself powered by GPTs, give it a try. You will be surprised how often you gain new insights by working with GPTs. I use them often to identify my own blindspots. 

## How to Start
- To initiate a meeting, type `"/start"` in the chat. This signals the bot to enter the meeting mode. 🚀

## Meeting Flow
### 1. Topic Definition
- As a user, you start by defining the topic of the meeting. This could range from technical discussions, scientific brainstorming, to engineering problem-solving. 📝 I tend to start strong, with at least 1000 words, describing the topic of the meeting at legnth. Remember, GPTs, at their core, are next-word prediction models and the context of the conversation will influence the prediction. You, as the user, should manage the content in the conversation by providing feedback and act as the moderator for the meeting. 

### 2. Expert Assignment
- Based on your topic, the bot simulates up to three experts (you can adjust this), each with specific expertise relevant to the discussion. These experts are not real individuals but personas created by the bot to facilitate the meeting. 👥 You can guide the GPT to define specific experts as you describe the topic of the meeting, in other words, your description of the topic of the meeting, will influence experts GPT will assign to the meeting.

### 3. Conversation Stages
- The meeting progresses through stages: **BEGINNING**, **MIDDLE**, and **ENDING**.
    - **BEGINNING**: The bot understands the topic and sets up the expert personas. 🌱 The GPT will define the experts in the meeting and you can ask it to edit them if you don't like the peronas.
    - **MIDDLE**: An interactive session where the experts (simulated by the bot) engage in the conversation, providing insights, asking questions, and assisting in idea development or problem-solving. 🔄 You, as the moderator of the meeting, can add feedback, highlight certain topics, ask specific expert to respond next, or simply say "Continue" and continue to read the expert's responses. I would like to have an active role in the conversation and avoide using "Continue" to often.
    - **ENDING**: The bot draws conclusions and provides final expert insights. 🎬 Often, the GPT can detect when is the best time to end the meeting, but feel free to ask the GPT to start the ENDING stage. Remember, you control the conversation. 

## Memory Files
- The bot utilizes memory files including previous discussions, a Q&A repository, and project details to inform its responses and maintain context. 📚 I have practiced with various files, but here I only mention the minimum set of files that are important to have productive meetings.
- The discussion.txt file often contains previous meeting, often as brainstorming sessions, or problem solving sessions. You may use the full text of the previous conversations or summary of previous meetings.
- The Q&A.txt file is the source of factual information. I populate this file with the responses I receive from PerplexityAI searchs. During #learning sessions with the GPT, it will generate the questions it needs to know and you can either respond to those questions yourselves (if you have the experties) or use resouces such as perplexity AI. So far, I do not like ChatGPT's web browsing performace for scientific applications, but I am sure soon (depends on OpenAI) GPTs will acquire the ability to connect or delegate tasks to other customized GPTs with better performances. Also, you can find academic papers that are relevant to your work which you prefer to include them in the knowledge base for your GPT. My approach is the same and I will upload the pdf within a #learning sesison and ask the GPT to generate questions, then ask those questions from the GPT or Perplexity AI to maintain an identical format within the Q&A.txt file. This process can also be automated if you want, but I tend to have an active role in what information goes into the Q&A.txt file.
- The projects.txt file contains the information about various projects you are working and it will help the GPT to organize its memory and identify gaps in its knowledge base (Q&A.txt). I tend to organize my projects as numbered-outline format and then add objectives and important key results to each section.

## Missions and Processes
- Depending on the session type (#brainstorming, #problem-solving, #learning), the bot follows specific processes to ensure goal-oriented and productive meetings. 🎯
- Brainstorming sessions are often a place to freely discuss an idea and the experts will help to imporve the idea by criticizing it and helping you to find solutions and ways to improve the idea.
- Problem-solving sessions can help you zoom into a probelm and analyze it from various perspectives. Having a well-organized projects.txt file will be useful for these conversations as problems are often specific to a projcect.
- learning sessions is your way of identifying gaps in your GPTs knowledge base (Q&A.txt). Given different projects you have, and the discussions you had previously, GPT can identify questions that it does not have an answer for them in the Q&A.txt file. I do not like to rely on GPTs internal knowledge and prefer a curated knowledge base as a text file. 

## Rules and Definitions
- The bot operates under a set of rules and definitions, emphasizing clarity, evidence-based decision-making, and constructive dialogue. 📖

## Conclusion
- **Technical Meeting GPT** is a powerful tool for simulating technical meetings, offering a unique blend of expertise and interactive dialogue. Whether you're brainstorming ideas or solving complex problems, this chatbot is here to guide you through! 💡
- Note that, as the user, you can control and moderate the conversation, curate the internal knowledge base for your GPT.
- The custom instruction file for a GPT must be less than 8000 character and the custom instruction for **Technical Meeting GPT** is already 7933 character. Feel free to modify, update, and experimnet with various parts of the instruction. There are many different ways that people are writing these custom instructions and the space keeps evolving.
- I recommend you to explore the space of GPT instuctions and experimnet with it.

<br>
<br>
Inspired by: 
- https://github.com/ProfSynapse/Synapse_CoR
- https://www.youtube.com/@DavidOndrej/
