# 🧠 TruthSync – Real-Time Fact Checking Bot for Discord

**TruthSync** is a 24/7 intelligent Discord bot designed to combat misinformation in real-time. It leverages the power of Google's **Gemini 2.0 Flash model** along with the **Grounded Search Tool** to analyze and verify the authenticity of any news or statement, directly within Discord.

---

## 🔗 Links

- 🔗 **Live MVP**: [https://h4b-frontend-nexuscode.vercel.app/](https://h4b-frontend-nexuscode.vercel.app/)  
- 💻 **Frontend GitHub**: [H4B-Frontend Repository](https://github.com/DevDesignWin/H4B-Frontend)  
- ⚙️ **Backend GitHub**: [H4B-Backend Repository](https://github.com/shauryapandit/H4B-Backend/tree/main)  

---

## 🚀 Features

- ✅ **24/7 Availability** – Always online and ready to verify!
- 🔍 **AI-Powered Fact Checking** – Backed by **Gemini and Grounded Search Tool** for accurate news validation.
- 💬 **Simple Usage** – Just use `!check <message>` to validate a claim.
- 🌐 **Cross-Platform Ready** – Works seamlessly on any Discord server.
- 📡 **Real-Time Results** – Instant feedback on whether the news is true, false, or misleading.
- 🛠️ Handles errors, invalid tokens, and misuse with graceful feedback.

---

## 💡 How It Works

1. User sends a message with `!check <message>` in Discord.
2. The backend processes the message and sends it to **Gemini and Google Grounded Search**.
3. Gemini evaluates the authenticity of the claim using multiple credible sources.
4. TruthSync responds in the server with whether the news is **true**, **false**, or **needs more context**, with a short explanation.

---

## 🛠️ Tech Stack

| Component        | Technology Used                                          |
|------------------|-----------------------------------------------------------|
| Frontend         | [Next.js](https://nextjs.org/)                            |
| Backend          | Python + [Gemini 2.0 Flash](https://ai.google.dev)        |
| Fact Check Engine| Gemini + Google Grounded Search Tool                      |
| Development IDE  | Firebase Studio                                           |
| Deployment       | Vercel (Frontend), AWS EC2 (Backend)                      |
| Discord Bot Lib  | [discord.py](https://discordpy.readthedocs.io/)          |
| Language Support | Multilingual Ready (Roadmap)                              |

---

## 🧪 Roadmap / Upcoming Features

- 🔗 **Source Linking** – View original fact-checking sources for transparency.
- 🌐 **Multilingual Support** – Verify news in multiple languages.
- 📈 **Fact-Check Analytics Dashboard** – Track what’s being verified most frequently.
- 🛡️ **Misinformation Alert System** – Real-time alerts for trending fake news.
- 🤖 **Cross-Platform Support** – Integration with **WhatsApp** and **Slack** coming soon.
- 📰 **Knowledge Base Integration** – A constantly updated news knowledge base to verify messages with real-time global events.

---

Built with ❤️ by developers who care about the **truth**.
