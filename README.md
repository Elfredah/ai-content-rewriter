# ✨ Friendly Content Rewriter – Built with Love by One Human and No Team

Hi! 👋 I'm Elfredah — a startup founder, content strategist, and self-taught builder.

As a solo creator wearing many hats, I constantly found myself fixing the same types of content: overly formal, robotic system messages, confusing buttons, or text that just didn’t feel human. 

Doing it manually, every single time? 😩 Not only tiring — but also unsustainable.

So I built **Friendly Content Rewriter** — a tiny but powerful tool that lets anyone instantly rewrite stiff, unclear text into something **friendlier**, **clearer**, and **more inclusive**, powered by AI.

---

## 🌱 What This Project Does

This tool allows users to:
- Paste short, formal, or complex content (e.g., UI messages or instructions)
- Click a button
- Receive a **rewritten version** that’s more accessible and human-centered
- Leverage **Meta’s LLaMA model via Hugging Face** to generate these rewrites

This project is part of a broader mission to **democratize smart tools** for creators — especially journalists, educators, and changemakers who don’t always have access to engineering support.

---

## 🛠️ How It Was Built

No developers. No designers. No analysts.

Just me — using:
- `HTML`, `CSS`, and `JavaScript` for the frontend
- `Python + Flask` for securely connecting to Hugging Face
- `GitHub` to manage the code
- **Hosted via GitHub Pages** and **tested locally with Flask**

It’s a simple, working prototype built by one person — but with big vision.

---

## 🔐 Using the Hugging Face API Securely

This project uses **Meta’s LLaMA model** through the Hugging Face Inference API.

To set up your own version:

1. Create a free Hugging Face account at [huggingface.co](https://huggingface.co)
2. Request access to a LLaMA model (like LLaMA 2 or 3)
3. Generate a **read-only API token** here: [huggingface.co/settings/tokens](https://huggingface.co/settings/tokens)
4. Save it in a `.env` file:


> ⚠️ **DO NOT** hardcode your token into your HTML, JavaScript, or public GitHub files.  
> Keep it in a `.env` file and **add `.env` to your `.gitignore`**.

---

## 🧱 Project Components

| Component         | Description                                              |
|------------------|----------------------------------------------------------|
| ✅ Flask Backend | Handles API requests securely, keeping token private     |
| ✅ HTML/CSS UI   | Clean and simple interface for pasting and rewriting text |
| 🔐 .env Handling | Keeps your Hugging Face token safe and secret            |
| 🌐 GitHub Pages  | Live static hosting for quick demo and sharing           |

---

## 🎯 End Goal

The goal is to create a simple tool that:
- Helps people rewrite content with clarity, warmth, and accessibility
- Demonstrates how AI (LLaMA) can be useful in small everyday writing tasks
- Is safe, transparent, and open-source

Whether you’re building for journalism, civic tech, or education — this tool aims to save you time and help you speak human-first.

---

## 🤝 Want to Collaborate?

If this project sparks ideas — whether you’re a writer, designer, developer, or AI enthusiast — feel free to fork, remix, or contribute.

I believe we don’t need big teams to build useful things.  
Just ideas, the right tools, and the will to start.

---

## 🙏 Thanks

To the open-source community: thank you for the tools and inspiration.  
To GitHub: thank you for giving indie creators like me a space to ship.  
And to anyone reading this — go build something you believe in.

—
**Elfredah Kevin-Alerechi**  
Founder, The Colonist Report | JournoTECH
