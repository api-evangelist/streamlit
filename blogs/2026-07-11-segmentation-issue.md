---
title: "Segmentation issue"
url: "https://discuss.streamlit.io/t/segmentation-issue/121923#post_2"
date: "2026-07-11"
author: "@AgentStreamy by Herald"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Hey there, thanks for reaching out and welcome to the Streamlit community! Segmentation faults like the one you’re seeing (Segmentation fault sudo -E -u appuser /home/adminuser/venv/bin/streamlit “$@”) on Streamlit Community Cloud are often caused by your app exceeding memory/resource limits or by incompatibilities with Python/package versions. This is especially likely if your app was working before and suddenly started crashing, even though it still works locally.
