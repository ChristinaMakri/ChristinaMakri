<div align="center">

### 🤖 cmakri-agent
<sub>🟢 online · profile agent for Christina Makri · AI Engineer</sub>

</div>

```console
$ cmakri-agent "Who is Christina and what does she build?"
```

<details>
<summary>💭 Thought for 2s</summary>

> The visitor wants a quick intro. I'll load Christina's profile, check what she builds, then share how to reach her.

</details>

```diff
● load_profile("cmakri")
  ⎿  ✓ profile found
+ name        Christina Makri
+ role        AI Engineer @ Netcompany
+ education   MSc in Artificial Intelligence
+ location    Thessaloniki, Greece
```

```diff
● search_work(focus="what she builds")
  ⎿  ✓ 4 results
+ 🤖  AI agents with tool calling
+ 🎙️  Voice agents
+ 📚  RAG over internal knowledge
+ 🏗️  Production-ready LLM applications
```

🤖 **Christina is an AI Engineer who builds LLM applications and AI agents, and makes them reliable enough for production.**

<details>
<summary>📖 read_file("about.md")</summary>
<br>

I started my career writing backend software, learning how production systems are built, maintained, and scaled. Over time, I found myself increasingly drawn to Artificial Intelligence, not because it was the latest trend, but because it changes the way software can solve problems.

Today I work as an AI Engineer, building applications around LLMs and AI agents. What I enjoy most isn’t the model itself; it’s everything around it: designing the architecture, connecting the pieces, making systems reliable, and turning an idea into something people can actually use.

I like working where software engineering meets AI. To me, good AI isn’t just about getting impressive responses. It’s about building systems that are dependable, maintainable, and ready for production.

</details>

```diff
● get_contact_links()
  ⎿  ✓ 2 links
```

💼 **[LinkedIn](https://www.linkedin.com/in/makri-christina/)** &nbsp;·&nbsp; 📧 **[cmakri1999@gmail.com](mailto:cmakri1999@gmail.com)**

<sub>✓ Task completed · 3 tool calls</sub>
