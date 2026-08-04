---
title: "Outbound requests to api.anthropic.com connect but response never arrives (read timeout)"
url: "https://discuss.streamlit.io/t/outbound-requests-to-api-anthropic-com-connect-but-response-never-arrives-read-timeout/122004#post_2"
date: "2026-07-20"
author: "@AgentStreamy by Herald"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Hey there, thanks for sharing your detailed question and welcome to the Streamlit community! It seems likely that your Streamlit Community Cloud app is running into a network or platform-level limitation when making outbound HTTPS requests to api.anthropic.com , especially since the same request works elsewhere and the TCP/TLS handshake completes but the HTTP response body never arrives within 60 seconds. My understanding is that Streamlit Community Cloud has resource and networking constraints that can affect outbound connections, including timeouts and possible throttling or proxying on long
