---
title: 'Meet ProdAI: My Open-Source AI Assistant'
date: 2024-05-27T01:43:46+08:00
draft:  false
---

Hey everyone!

I’m super excited to share something I’ve been working on – **[ProdAI](https://github.com/isaganijaen/prodai)**, my very own open-source AI assistant. If you’ve ever wanted a handy AI buddy to help with your daily tasks, answer questions, or just have a chat, then you’re going to love this. Let me walk you through what ProdAI is, how it works, and how you can set it up for yourself.

## What’s ProdAI?
ProdAI is like having your personal assistant that’s always ready to help. Built with some cool web technologies, it uses AI models to handle a bunch of different tasks. Whether you need some brainstorming help, content writing, or just a friendly conversation, ProdAI has got your back.

## Cool Features
### 1. AI Conversations
ProdAI can chat with you and help with ideas, write stuff, or just talk about anything. It’s like having a smart friend who’s always available.

### 2. Pick Your Model
You can choose from different AI models based on what you need. Right now, ProdAI supports models like Gemma-1.1-2b int4 and Gemma-2b int8. So, you get to pick the one that works best for you.

### 3. Conversation History (Currently in-progress)
ProdAI keeps track of your chats, so you can go back and see what you talked about. No need to worry about losing important info!

### 4. Customize Your Look
Built with Vue.js and Tailwind CSS, ProdAI looks clean and modern. You can tweak the interface to match your style – change themes, layouts, you name it.

## How It Works
ProdAI is made with HTML, CSS, and JavaScript, and it’s super easy to use. Here’s a quick look at how it all fits together:

 - Frontend: The interface is made with HTML and styled with Tailwind CSS and DaisyUI. Vue.js handles all the dynamic parts, making everything smooth and interactive.
 - Backend: You can switch between AI models through a simple dropdown menu. The app uses marked.js to render Markdown content, so text interactions look great.

## Getting Started with ProdAI
Setting up ProdAI is a breeze. Just follow these steps:

1. Clone the Repo: Grab the ProdAI code from GitHub and put it on your computer.

```bash
Copy code
git clone https://github.com/yourusername/prodai.git
cd prodai
```



2. Download Gemma 2B (TensorFlow Lite 2b-it-gpu-int4 or 2b-it-gpu-int8) or convert an external LLM (Phi-2, Falcon, or StableLM) following the guide (only gpu backend is currently supported), into the your folder.
3. In your ```index.js``` file, update ```modelFileName``` with your model file's name.
4. Run ```python3 -m http.server 8000``` under your folder to host the three files (or ```python -m SimpleHTTPServer 8000``` for older python versions).
5. Open localhost:8000 in Chrome. Then the button on the webpage will be enabled when the task is ready (~10 seconds).
6. Choose a Model: Pick the AI model you want from the sidebar dropdown. ProdAI will load it up, and you can start chatting right away.

***Note**: You may use Live Server in your VS Code if you don't want to use python.*


## Make It Your Own
The best part about ProdAI is that you can customize it however you like. Here are a few ideas:

- Change the Theme: Tweak the Tailwind CSS settings to create a look that’s all you.
- Add New Models: Update the model selection component in Vue.js to add more AI models.
- Add Features: Want voice recognition, task management, or scheduling? Go ahead and add them to ProdAI.

## Wrap-Up
ProdAI isn’t just an AI assistant – it’s a way to bring AI into your daily life and make it work for you. Since it’s open-source, you can customize it, contribute to it, and make it even better.

I hope you have as much fun using ProdAI as I had making it. Check out the GitHub repository to get started, and let me know what you think. Your feedback and contributions are always welcome!

Happy hacking!

