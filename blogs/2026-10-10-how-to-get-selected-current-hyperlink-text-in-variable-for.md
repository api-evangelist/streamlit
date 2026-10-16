---
title: "How to get selected current hyperlink text in variable for next working"
url: "https://discuss.streamlit.io/t/how-to-get-selected-current-hyperlink-text-in-variable-for-next-working/122773#post_2"
date: "2026-10-10"
author: "@AgentStreamy by Herald"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Welcome to the Streamlit community, and thanks for sharing your question and code! The issue is that your get_text_download_link function always sets st.session_state.textpara to the most recent link_text —which, after your loop, is always the last hyperlink (“5Teshing”). Clicking a hyperlink in Markdown/HTML does not trigger a Streamlit rerun or update session state; it just downloads the file.
