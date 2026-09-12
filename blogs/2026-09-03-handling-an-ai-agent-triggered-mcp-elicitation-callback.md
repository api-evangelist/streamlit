---
title: "Handling an AI Agent triggered MCP Elicitation callback"
url: "https://discuss.streamlit.io/t/handling-an-ai-agent-triggered-mcp-elicitation-callback/119502#post_2"
date: "2026-09-03"
author: "@Ricart Ricart"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
I’d treat the elicitation callback as an out-of-band request rather than trying to render UI from inside it. The pattern I’d prototype is a background MCP session that writes the pending request into per-session state, then lets a normal Streamlit rerun render the form and pass the result back through a synchronization primitive. I don’t have a verified end-to-end example to claim this works with the current SDK callback contract, so that return contract and the cross-thread behavior are the first things I’d test.
