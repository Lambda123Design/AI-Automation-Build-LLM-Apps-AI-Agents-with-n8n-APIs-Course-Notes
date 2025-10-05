# AI-Automation-Build-LLM-Apps-AI-Agents-with-n8n-APIs-Course-Notes
This Repository contains my notes of "AI Automation: Build LLM Apps &amp; AI-Agents with n8n &amp; APIs" Course

**Tools in the Course:** Zapier, make, n8n, LangChain, LangGraph, Langflow, Flowwise AI (Best with LangChain), AutoGen, CrewAI, Swarm (OpenAI), VectorShift, VoiceFlow, BotPress

**Table of Contents:**

**I) Introduction**

**A) Course Overview**

**B) Important Tips for the Course**

**C) Explanation of the Links that you need in the Course**

**D) Instructor Introduction: Arnold Oberleiter (Arnie)**

**II) Basics – Automation, LLMs, Function Calling, Vector Databases & RAG Explained**

**A) What to Expect in This Section**

**B) What Are Automations, AI Automation, and AI Agents?**

**C) What Is an API (Client and Server)**

**D) Tools for Automation & AI Agents: n8n, Make, Zapier, LangChain, Flowise & More**

**E) What are LLMs like ChatGPT, Claude, Gemini, Llama, Deepseek, Grok etc.**

**F) OpenAI API Explained: Pricing, Project Setup, Management & Compliance**

**G) Test Time Compute (TTS) Explained: Thinking Models like Deepseek R1 & OpenAI o3**

**H) What is Function Calling in LLMs for AI Agents and AI Automations**

**I) Vector Databases, Embedding Models & Retrieval-Augmented Generation (RAG)**

**J) Key Takeaways**

# **I) Introduction**

**A) Course Overview**

Welcome to the course! First of all, thank you for making the right decision. My name is Arnie, and in this course, you will learn everything about automations, AI automations, and AI agents, with a focus on tools like KNN, Make, Zapier, LangChain, Flowise, and more. Since this is a comprehensive course, we start with a course overview where the content structure is explained, followed by tips on how to use the course links effectively. In Section Two, we cover the fundamentals, explaining what automations, AI automations, and AI agents are, as well as the concept of APIs since these are heavily used throughout the course. We also introduce the tools for building automations and agents and dive into understanding LLMs, the brain of these automations. Topics like the OpenAI API, token pricing, project setup, compliance, test-time compute, and the use of reasoning models are covered. Additionally, function calling, vector databases, and embedding models are explained because they are crucial for agent technology. Although experienced users can skip these basics, it is highly recommended to understand them for a solid foundation.

Section Three shifts to practical implementation. We start by demonstrating local installation, node version management, updates, and testing, along with a free cloud setup. From here, learners build their first automation, with downloadable JSON resources for easy import into their own instances. The course then progresses to slightly more complex automations, such as storing Airtable data locally and connecting Google Sheets with Google Cloud Platform. Section Four focuses on expanding automations to AI-powered workflows, starting with an email automation using Gmail and Airtable, followed by sentiment analysis using an LM. Learners also explore open-source LLMs like DeepScr1, LLaMA, and Mistral, learning how to integrate any LLM via an API into an addon.

Section Five introduces agents and Rack applications. The course covers upserting data automatically into a vector database using Google Drive triggers and building a Rack chatbot connected to that database. Next, learners build an email agent with sub-workflows, vector database integration, and Google Sheets support. Tips for quickly automating email summarization, filtering, and auto-reply are provided. Section Six is dedicated to prompt engineering for AI agents and automations, focusing on system prompts, with downloadable GPT-2 prompts provided. In Section Seven, learners tackle hosting applications and building agents for WhatsApp and Telegram, including self-hosting on Render, using AI agents with sub-workflows, dynamic expressions, and voice integration. Large agents with multiple sub-workflows and practical social media scraping examples are also included, along with advanced tips for prompt design.

Section Eight emphasizes debugging workflows using webhooks and HTTP request nodes. Learners create error-trigger workflows, connect Flowise to addons via webhooks, and utilize simple JavaScript to troubleshoot workflow issues, including practical examples. Section Nine introduces the Model Context Protocol (MCP), explaining the concept and connecting Cloud Desktop with KNN to turn it into an agent. Techniques for building server-client structures within an addon are also covered. Section Nine continues by guiding learners to monetize AI agents, embedding them into web pages, building market-ready Rack applications that gather leads, hosting standalone apps, integrating applications into websites, applying custom CSS branding, and optimizing sales strategies. Tips for fast lead scraping are provided as well.

Section Ten focuses on optimizing Rack applications, covering data quality, chunk size, overlap, and embedding models. Learners learn how to scrape HTML pages and convert content to Markdown, work with PDFs, and prepare data using Llama Index with Llama Bars for better embeddings. The importance of chunk size and overlap is explained to ensure correct embedding model performance. Section Eleven addresses compliance, security, and ethical considerations. Issues such as jailbreaks, prompt injections, data poisoning, copyright, intellectual property, privacy, and data protection are discussed. Learners also explore censorship, alignment, bias in LLMs, licensing of addons, GDPR, CCPA, CPRA, UAE regulations, and related compliance measures.

Finally, the course concludes with a “What’s Next” section, summarizing the journey and expressing gratitude to learners for investing their valuable time. The instructor emphasizes that, while some concepts may seem complex initially, following the course step by step will provide both theoretical understanding and practical implementation skills in AI automations and agents.

**B) Important Tips for the Course**

In this session, the instructor begins by welcoming learners and sharing a few tips to maximize learning from the course. He emphasizes that some people may find the pace of his speech slow, but this can easily be adjusted. Learners can increase the video playback speed using Google Chrome extensions or the platform’s built-in controls, which can go up to 2x speed. Consuming content at a faster, personalized pace keeps the brain fully engaged and focused, preventing it from wandering or generating unrelated thoughts, similar to reading a book too slowly. The key is to find a speed that allows 100% focus on the material.

The instructor then outlines his personal goals: spreading AI knowledge and building an AI community. He highlights the general aim of the course, which is to provide learners with a comprehensive understanding of LLMs, their basics, and their practical applications, including building AI agents and running models locally. He notes that while many people view AI and LLMs as complex or mysterious, the concepts are easier to grasp than commonly perceived. The course emphasizes the use of the tool Nadan to build AI automations and AI agents in a structured, project-based approach.

Throughout the course, learners will engage in hands-on projects available in downloadable JSON format. The curriculum begins with simple automations, such as handling form submissions and storing data in Airtable. It progresses to sentiment analysis with LLMs, Google Sheets integration, and simple chat-triggered agents capable of sending emails using various LLMs like Claude, Debussy, and ChatGPT. More advanced projects include building agents that automate social media, summarize emails, scrape GitHub, and store data in Pinecone vector databases. Learners also create Rack applications that can be monetized and used for lead generation, convert HTML web pages into Markdown, and develop WhatsApp and Telegram agents with calendar and email functionality.

The course pushes the boundaries by guiding learners to create large, multi-functional agents capable of triggering multiple sub-workflows. Examples include a mail agent that automates emails entirely and a larger agent that interacts with users humorously while managing tasks. There is also an error workflow to detect and address failures immediately. Overall, the course provides comprehensive coverage of AI automations and LLM-based agents, ensuring that learners gain practical skills and knowledge applicable to real-world workflows. Learners can expect a constantly updated curriculum and the opportunity to provide feedback or suggest additional content for inclusion.

**C) Explanation of the Links that you need in the Course**

In this lecture, the instructor addresses common questions about where to find important resources and links used throughout the course. He provides a centralized reference containing all essential links, including downloads for Nadan, NVM, and the Nylon web page, as well as GitHub repositories. The links also cover self-hosting on Render, the IPsec Grok platform, the OpenAI Playground, entropic models with APIs, Google AI Studio, the Facebook Developer Console, Google Cloud Console, Pinecone for vector stores, Olama, Podfather for Telegram, FireCrawl, Julia PDF-to-Markdown, and Llama Index PDFs for Rack on GitHub. Additionally, learners are guided to a Google Colab notebook that will be used later in the course, information about Ignite and licensing, GDPR and AI Act compliance materials, the LLM leaderboard, and software tools for building AI automations and agents such as Zapier, Make, LangChain, LangFlow, and Flowwise.

The instructor recommends downloading the provided PDF file via the course resources section, which consolidates all these links into one accessible document. This ensures that learners have a single reference file containing every link used throughout the course, making it easier to access resources quickly and efficiently. He also mentions that in later sections, downloads will mostly include JSON workflows or links to GPT resources, maintaining consistency in how materials are shared.

**D) Instructor Introduction: Arnold Oberleiter (Arnie)**

He is AI enthusiast, build AI for small businesses. Also, started his own Youtube Channel

# **II) Basics – Automation, LLMs, Function Calling, Vector Databases & RAG Explained**

**A) What to Expect in This Section**

In this section, you will begin by exploring some of the most important foundational concepts needed before diving deep into building AI automation systems. The first part introduces you to what automations are in general, followed by AI automations and AI agents. Understanding these terms is essential, as they form the basis of how intelligent systems can automate repetitive tasks, make decisions, and perform actions on their own.

After understanding these core ideas, you will get a broad overview of various platforms that are widely used for creating automations. This includes popular no-code and low-code automation tools like Zapier and Make.com, as well as platforms from the LangChain ecosystem such as LangGraph, Flowise, CrewAI, Autogen, and several others. These tools allow you to build and orchestrate complex workflows that connect multiple AI models and external applications.

Because automations often rely heavily on APIs (Application Programming Interfaces), this section will also cover what an API actually is and how it works. You’ll learn how APIs enable communication between different systems, making it possible for your automations to interact with various services and data sources. Additionally, you’ll be shown how to create new projects, generate and manage API keys, and understand how API integration forms the backbone of most AI-driven systems.

Next, you will learn about LLMs (Large Language Models) — the brain of most AI automations. This part explains in detail what an LLM is, how it functions internally, and how it processes and generates language. Alongside this, the concept of tokens will be introduced. Tokens are the basic units of text that LLMs use to understand and generate responses, and knowing how they work is important for understanding OpenAI’s API pricing and model selection. You’ll also learn about different model types, including those with test-time compute, and how to choose the right one for your use case.

The next concept you’ll study is function calling, a critical feature that allows AI agents to use external tools and perform tasks beyond text generation. Understanding function calling is key because this is how agents connect with APIs, databases, or even perform actions like sending messages, retrieving data, or controlling applications autonomously.

Following that, the section introduces you to vector databases, retrieval technologies, and embedding models. These topics explain how AI systems store and recall information efficiently, allowing them to maintain memory, context, and relevance when working with large sets of unstructured data. This is a crucial part of building intelligent agents that can reason and interact dynamically with information.

Finally, the instructor emphasizes that while some learners may already be familiar with these topics, it is strongly recommended to go through this section carefully. A solid understanding of these fundamentals—APIs, tokens, LLMs, embeddings, and function calling—is essential for mastering the advanced practical implementations later in the course. Although you can skip this part if you wish to jump straight into practice, taking time to grasp these theoretical concepts will significantly improve your ability to design and build powerful AI automation systems in the future.

**B) What Are Automations, AI Automation, and AI Agents?**

This section opens by insisting we first define a few core words so there’s no confusion: automations, AI automations, and AI agents. The plain definition of an automation is technology performing tasks automatically without human intervention. Crucially, every (normal) automation is built from at least two parts: a trigger (something that happens) and an action (what the system does when the trigger fires). Even the simplest automation — a single trigger linked to a single action — qualifies; more complex flows can have cascades of triggers and actions.

A concrete, simple example used throughout the lesson is a form-submission automation. You embed a form on a site, that submission is the trigger, and the action writes the data into Airtable using Airtable’s API. You can test the workflow by submitting different names/choices (e.g., “Arnie — deluxe room”, “Bob — single room”) and watch the automation run and store the rows automatically. This demonstrates how automation works end-to-end: the form triggers the workflow, the workflow calls an API, and the data is stored — all without human intervention.

Triggers and actions can be extremely varied. Triggers may come from WhatsApp, Telegram, email, Airtable or Google Sheets updates, webhook calls, scheduled timers, social platforms (Reddit, Facebook leads), manual triggers, or another workflow calling the one you built. Actions can post to social media, insert rows, send messages, label emails, etc. You can also use schedulers (e.g., post two times a day), webhooks (called by other systems), or human-in-the-loop steps — so even “normal” automations can become very rich and flexible.

An AI automation is the same trigger→action pattern, but with an LLM as the brain inside the flow. Instead of passing raw variables unaltered, the system sends text (or data) to an LLM (ChatGPT, Claude, Gemini, Llama, etc.) which performs intelligent transformations — summarization, data conversion, sentiment analysis, classification, extraction, and so on — and returns a result that becomes the action’s input. The example given is a form submission containing a user review: the LLM performs sentiment analysis and returns a single word ("positive"), which is then stored in Google Sheets. That intelligent conversion is what turns a normal automation into an AI automation.

An AI agent takes the idea one step further: the LLM (the brain) not only reasons about text but also has tools it can call or can call other LLMs/sub-workflows. In practice this means the agent can directly interact with external services (Gmail, Calendar, file systems, search APIs, etc.) and perform actions autonomously. The example: a Telegram trigger talks to an agent whose tools include “Gmail summary” and a Calendar tool. You can tell the agent “Summarize my last five emails” or “Invite Ani to my birthday,” and the agent will use the Gmail tool to read/label/send emails and the Calendar tool to create events — then respond to you in Telegram. The agent also retains conversational memory of the interaction.

The course contrasts small agents and large, composite agents. A large agent uses many sub-workflows and possibly multiple LLM chains (you can change which LLM is the “brain”), plus specialized helper agents: a research agent that queries Hacker News, SERP APIs or Wikipedia; an email agent that can fetch, label, mark read/unread, and otherwise manage your inbox; and other domain experts. Asking the main agent to “write a post on X” can trigger a sub-workflow; asking it to “search Hacker News” triggers the research agent. Those helper agents may themselves use tools, making the whole system layered and modular.

When an LLM calls tools or external code, that mechanism is commonly referred to as function calling. Tools can include typical “software 1.0” primitives (Python interpreters, terminals, file operations), media generators (audio/video), and data/retrieval systems (embeddings + vector databases). The instructor uses the analogy that an LLM’s context window is like RAM — it holds the information the model can attend to — and stresses that agents can talk to other LLMs and invoke specialized toolchains (e.g., an embedder, a Python runtime, or a search API) to extend their capabilities.

The material also highlights organizational metaphors and future directions: Andrew Karpathy’s framing (and other writings such as Botpress’s article) suggest treating an LLM that can use tools as a reagent/agent, and you can build an entire “organization” of agents. In that structure a top-level LLM acts like a CEO that delegates to specialized “employees” (CFO, CTO, general counsel, chief scientist, etc.). Each worker agent can have its own tools and responsibilities, and the CEO coordinates them — enabling sophisticated, multi-step problem solving across agents.

Finally, the instructor reassures learners this will be shown slowly and practically. You’ll see step-by-step demos (APIs, function calling, embedding/DBs, tools, sub-workflows) and learn how to create projects and manage API keys. If you already know some parts you can skip ahead, but it’s strongly recommended to master these fundamentals because they form the backbone of everything that follows: triggers, actions, LLM brains, function calling, tool use, and agent orchestration. In short: automation = trigger + action; AI automation = trigger + action + LLM brain; AI agent = LLM brain + tools (and often sub-agents), able to call functions, other LLMs and external services to operate autonomously.

**C) What Is an API (Client and Server)**

In this part of the course, the focus shifts to understanding what an API is — a crucial concept needed before building complex automations and AI agents. The instructor begins by reminding you that every automation or agent you build involves one or more APIs. For example, an AI agent that uses ChatGPT in the background must communicate with OpenAI’s API to generate responses. Similarly, if the same agent stores or retrieves information from Pinecone, a vector database, it must use the Pinecone API to exchange data. Even integrations with Google Sheets require interaction with the Google Sheets API. Therefore, understanding APIs is essential because they form the connection points that enable these different software systems to communicate and work together.

To explain APIs in simple terms, the instructor references Amazon Web Services (AWS), which provides one of the clearest definitions. According to AWS, APIs (Application Programming Interfaces) are software components that allow two or more software systems to communicate with each other using a set of predefined definitions and protocols. A helpful example is given: imagine a Weather Bureau system that stores daily weather data. When you open a weather app on your phone, your app communicates with this system’s API to request data. The system then sends back the current weather conditions, which appear on your phone. This interaction — where your phone requests information and receives a response — is an API call.

The term API itself stands for Application Programming Interface. Here, the word application refers to any software performing a specific function, and the interface is the defined method or “contract” that explains how two pieces of software can talk to one another. Essentially, an API serves as a contract of service between two applications, specifying the rules for how requests are made and how responses are returned. The details of this “contract” are found in the API documentation, which provides developers with the exact format and structure required to send valid requests and interpret the responses correctly.

To simplify further, APIs always involve two main entities — a client and a server. The client is the application that sends a request, while the server is the system that receives the request, processes it, and sends back a response. Using the earlier weather example, your mobile app (the client) sends a request to the Weather Bureau’s database (the server), asking for weather updates. The server then responds with the requested data, which the app displays to you. This client-server interaction forms the foundation of how most APIs operate in modern software systems.

While there are various types and protocols of APIs, such as REST, SOAP, and GraphQL, the instructor emphasizes that for the scope of this course, understanding the core concept — that APIs connect software systems and enable communication — is enough. The goal isn’t to memorize every technical detail but to grasp how to use APIs effectively in automations and AI workflows.

The section concludes by reinforcing the key takeaway: an API is simply a connection point that allows two software systems to “talk” to each other. Whether it’s connecting your phone to a weather service, linking a form submission to Airtable, or connecting an AI agent to tools like Pinecone or Google Sheets, the principle is the same. The client sends a request, the server responds, and the API facilitates that communication. Throughout the rest of the course, you’ll use many APIs — sending requests, receiving data, and executing actions — which makes understanding this foundational concept critical for building intelligent automations and AI agents.

**D) Tools for Automation & AI Agents: n8n, Make, Zapier, LangChain, Flowise & More**

In this video, the speaker provides a broad overview of several major platforms that are great for automation, AI automations, and AI agents. The goal is to introduce what tools exist in the market, their strengths, and their weaknesses — setting the stage for deeper exploration in later lessons.

The first platform introduced is Zapier, a long-standing tool for creating basic automations. While Zapier is user-friendly and suitable for simple workflows, it has limitations and eventually requires a paid subscription. Due to these constraints, the speaker mentions that Zapier won’t be covered in depth since it’s not ideal for building complex AI agents.

Next is Make, another popular automation tool. Make allows users to create both standard and AI-powered automations. However, like Zapier, it comes with restrictions — especially when it comes to building complete AI agents — and it also requires payment for advanced usage. While Make is considered a solid platform overall, its limitations make it less suited for full-fledged agent creation.

The video then moves to N8N (pronounced "N-nine"), which the speaker highlights as one of the best and most powerful platforms available. N8N supports automations, AI automations, and AI agents, offering vast flexibility. What makes it stand out is that it’s completely open source, allowing users to download the source code from GitHub, install it locally, and use it for free. N8N also supports hosted versions, but even without paying, it remains fully functional. The speaker emphasizes that N8N has recently exploded in popularity and will be the main focus tool throughout the course.

Following that, the discussion turns to LangChain, one of the most well-known ecosystems for building AI applications and agents, particularly in Python. LangChain has a vast and well-developed ecosystem that collaborates with many companies. Within the LangChain family, the speaker introduces LangGraph, which simplifies the creation of AI agents through visual workflows. Built on top of LangGraph is LangFlow, which works similarly but provides a more visual drag-and-drop interface for designing chains and agents.

However, the speaker recommends using Flowise, which also leverages LangGraph under the hood but offers a far better visual interface and ease of use. Flowise allows users to design complex agent workflows with drag-and-drop functionality and integrate multiple components seamlessly. The course will also include a few sessions on Flowise and even demonstrate how it can connect with N8N for powerful automation workflows.

The video then introduces Autogen, a tool developed by Microsoft. Unlike N8N or Flowise, Autogen is primarily focused on AI agent creation and doesn’t support general automations. The speaker finds Autogen somewhat complex to use and not particularly enjoyable, but still acknowledges its relevance. It’s open source and available on GitHub, where users can find installation instructions and even free courses to learn it.

Another platform mentioned is Crew AI, which was quite popular in the past. However, the speaker notes that N8N has since surpassed it in capabilities and user interest. Alongside Crew AI, the video also touches on Swarm, a newer open-source framework developed by OpenAI. While Swarm has gained some attention on GitHub, it still lacks robust features and remains in early stages of development.

Next, the speaker discusses Agency Swarm, a framework specifically designed for AI agent creation in Python. Although it offers high levels of customization, it is more technical and complicated to use, making it less accessible for beginners or users seeking simplicity.

The speaker then briefly mentions Vector Shift — a user-friendly platform with an easy interface that supports AI agents and automations, though it may require payment for premium features. Similar to Vector Shift, there’s Voiceflow, another tool suitable for automation and conversational agent creation. Additionally, Podpress is introduced — an easy-to-use yet highly expensive platform. The pricing is considered excessive, with team plans costing around $445 per month, which the speaker deems unreasonable compared to the free flexibility of N8N.

To summarize, the video highlights that there are many different frameworks available for automation and AI agents — including Zapier, Make, N8N, LangChain, Flowise, Autogen, Crew AI, Swarm, Agency Swarm, Vector Shift, Voiceflow, and Podpress. Among these, N8N stands out as the most powerful, customizable, and cost-effective platform, capable of handling automations, AI automations, and AI agents all in one. It’s open source, free to use, and ideal for both beginners and advanced users.

The speaker concludes by emphasizing that while there are countless tools available — and new updates might make others more appealing in the future — for now, N8N is the platform of choice. If another tool eventually improves significantly, it can easily be adopted later. But as of now, N8N is the go-to tool for AI automation and agent development.

**E) What are LLMs like ChatGPT, Claude, Gemini, Llama, Deepseek, Grok etc.**

In this video, the instructor explains the concept of Large Language Models (LLMs) — the “brain” behind AI agents and AI automations. Every AI agent requires a brain to process information and generate responses, and that brain is an LLM. For example, in the discussed setup, ChatGPT serves as the LLM or the “brain” of the AI agent. However, ChatGPT is just one example. There are many different LLMs available today, such as Grok, GPT models, Gemini models, DeepFake (open-source) models, Claude, LLaMA, and Mistral, among others. Although they vary in scale, ownership, and capabilities, they all share a common underlying principle — they process and generate text using learned patterns from massive datasets.

Before understanding how these AI agents operate, it’s essential to grasp what an LLM actually is and how it works internally, especially since using them via APIs also involves paying for tokens. The instructor simplifies the explanation using an open-source example — Meta’s LLaMA 2 model, which helps to visualize the components of any LLM. Essentially, an LLM consists of two core files:

The Parameter File (P) – This is the main file that contains the model’s learned parameters.

The Run File – A smaller file that contains the code (often written in Python or C) needed to execute the model using the parameter data.

The parameter file is where the intelligence of the model resides. For instance, the LLaMA 2 (70B) model contains 70 billion parameters. These parameters are the learned “weights” that encode patterns, structures, and relationships in language. To train this parameter file, researchers use massive amounts of text data — up to 10 terabytes of text from diverse sources like Wikipedia, websites, and books. This huge dataset is then compressed into the 140GB parameter file — similar to how a ZIP file compresses data.

This compression requires an enormous amount of GPU power, which explains why GPU companies like NVIDIA have become so valuable. Since November 2022, when ChatGPT was released, the demand for GPUs skyrocketed because every major AI company needed powerful hardware to train models.

The run file, by contrast, is much smaller — typically around 500 lines of code — and serves to load and execute the parameter file. When you use an open-source LLM such as LLaMA 2 or LLaMA 3, you can download both of these files and run them locally on your computer. This allows complete data privacy, since no information leaves your system. However, with closed-source models like OpenAI’s GPT or Anthropic’s Claude, you cannot access or download these files. You must interact with them through a web interface or API, which means your data travels over the internet.

The instructor then explains how an LLM actually learns. In simple terms, an LLM is built upon the transformer architecture, which is a type of neural network that processes and predicts words based on previous context. The model learns language through three main phases of training:

Pre-training:
During this phase, the model reads and learns from massive amounts of text data (around 10TB) and compresses it into a parameter file. This helps it understand grammar, semantics, and relationships between words. The model learns to predict the next word based on the sequence it has already seen. This phase requires extremely powerful GPUs and significant computational resources.

Fine-tuning:
Once the base model is pre-trained, it is refined using smaller datasets — typically around 100,000 examples — that show how humans expect responses to look. The model is provided with example questions and human-preferred answers, teaching it how to respond in a more human-like and helpful manner. This stage is less resource-intensive and focuses on improving response quality.

Reinforcement Learning (RLHF – Reinforcement Learning with Human Feedback):
After fine-tuning, the model goes through a final stage where human evaluators or automated systems rate the responses (thumbs up or down). The model learns which responses are considered better and improves accordingly. This step further aligns the model with human preferences.

These three phases — pre-training, fine-tuning, and reinforcement learning — are the foundation of how all modern LLMs are trained.

The instructor then shifts focus to tokens, which are the numerical representations of text that LLMs process internally. When you input text, the LLM converts words into tokens, which are small pieces of text (not always full words). For example, “invisible” might become two tokens, while punctuation marks like periods are treated as separate tokens. The model performs its calculations using these token IDs — numbers that represent linguistic units.

Understanding tokens is important because every LLM has a token limit, meaning it can only process a fixed number of tokens at a time. For instance, OpenAI’s GPT-4 Turbo can handle around 128,000 tokens, equivalent to roughly 100,000 words of text. Smaller models might have limits of 4,000 tokens, while newer ones can go up to 2 million tokens. Once this limit is reached, the model forgets earlier parts of the conversation, since it can only “see” the most recent tokens — known as its context window.

To illustrate, the instructor gives a ChatGPT example: If you ask it to write a story about a fox and then later about a frog, as you continue generating more tokens, the model eventually forgets the earlier fox story once the token limit is reached. Hence, the model “remembers” only the last portion of the conversation. This is why long conversations sometimes cause ChatGPT to lose earlier context.

Additionally, generating tokens through APIs costs money. For every token processed (both input and output), API users pay a small fee. The exact cost varies by model and will be explained in the next video. However, using open-source models locally avoids these costs entirely, since the computations happen on your own system.

In summary, this video explains how an LLM acts as the brain of an AI agent. It consists of two files — a parameter file (which contains the compressed intelligence) and a run file (which executes the model). Training involves three main steps: pre-training, fine-tuning, and reinforcement learning. LLMs process language using tokens, which represent text as numbers, allowing the neural network to predict the next likely word. Every model has a token limit, determining how much it can “remember.” Open-source models can be run locally for free, while closed-source ones require APIs and payment. Finally, the instructor emphasizes that prompt engineering — asking well-structured questions — plays a vital role in getting better responses from LLMs.

The session ends with the reassurance that while the explanation was kept simple and high-level, this foundational understanding is sufficient for effectively working with LLMs and building powerful AI automations and agents.

**F) OpenAI API Explained: Pricing, Project Setup, Management & Compliance**

**G) Test Time Compute (TTS) Explained: Thinking Models like Deepseek R1 & OpenAI o3**

**H) What is Function Calling in LLMs for AI Agents and AI Automations**

**I) Vector Databases, Embedding Models & Retrieval-Augmented Generation (RAG)**

**J) Key Takeaways**
