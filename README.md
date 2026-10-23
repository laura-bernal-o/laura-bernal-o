## Hi, I'm Laura Bernal

MBA candidate at UC Berkeley Haas (2028) · aspiring Product Manager · industrial engineer who builds

I've spent six years in growth, strategy and product-adjacent roles at startups: a group-buying marketplace and a Series A fintech in Latin America, and then a US sports app. In each of them my work came down to the same thing: understanding user behavior, then turning that into a decision about what to build or fix next.

At Haas I'm learning to build the tools myself, with a focus on agentic AI. This GitHub collects those builds. Most of them start with a product question rather than a technical one.

LinkedIn · laurabernal@berkeley.edu

Featured projects
🎧 Spotify Review Insight Pipeline · Live dashboard

Product question: Spotify has 660K Google Play reviews. Which issue should the team prioritize next quarter?

A multi-agent pipeline (Python, Claude Haiku and Sonnet, Postgres, Vercel) that ingests every review, classifies topic, intent and severity, groups them into issues and ranks those issues
Labels are checked against a human-labeled golden set (88% intent agreement) and an independent AI verifier
Code computes every number in the final memo, and claims without supporting data are rejected. A per-run spend cap kept the whole project at about $3.45
Recommendation: prioritize playback reliability
🤝 Networking Tracker · Live app

Product question: How can MBA students keep track of the people they meet during recruiting, so no follow-up falls through the cracks?

A full-stack web app built with Next.js, TypeScript, Neon Postgres and Better Auth, and deployed on Vercel
Supports search, priority filters and sorting, with a responsive layout for desktop and mobile
Each user's contacts are private, enforced in the database through Row-Level Security
📚 Personal Wiki

Product question: Can I ask questions about my own course notes and get cited answers, without sending my data to the cloud?

A Python command-line tool that turns raw notes into a linked Obsidian wiki and answers questions with retrieval-augmented generation (RAG), using a local Gemma model
Uses hybrid search (keyword plus embeddings), and every answer cites its sources, with a check that flags unsupported citations
The README documents the limitations honestly, including answer speed and when the chat assistant fails to search, and proposes a fix
🧠 Custom LLM

Product question: What does a language model actually learn from its training data, and what doesn't it learn?

I trained a small GPT-style model from scratch, twice, and built a 48-case evaluation suite to compare the two runs
Expanding the training data raised the model's score on the evaluation cases it could be tested on from 83% to 100%. The experiment also showed that a model can learn sentence patterns without learning the vocabulary it needs to use them
🕹️ Ms. Pac-Man DQN

Product question: Can a reinforcement-learning agent learn to play Ms. Pac-Man from screen pixels alone?

A Deep Q-Network built in PyTorch. It raised the mean score by 91% after training
The analysis also covers what didn't improve (the agent's survival time) and why
Toolkit

Analysis: SQL · Python · R · Excel · Power BI · Amplitude · CleverTap Building: Claude Code · TypeScript / Next.js · Postgres (Neon) · Vercel · PyTorch · Ollama AI: multi-agent pipelines · RAG · LLM evaluation · reinforcement learning

<!--
**laura-bernal-o/laura-bernal-o** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
