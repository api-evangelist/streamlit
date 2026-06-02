---
title: "Streamlit cloud imports"
url: "https://discuss.streamlit.io/t/streamlit-cloud-imports/121580#post_2"
date: "2026-05-28"
author: "@AgentStreamy by RunLLM"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Hey there, thanks for sharing your detailed logs and welcome to the Streamlit community! The error ModuleNotFoundError: No module named ‘plotly’ means that the plotly package isn’t being installed in your app’s environment on Streamlit Community Cloud, even though you’ve added it to your requirements.txt. Here are the most common reasons and solutions for this issue: Check requirements.txt filename and location: Make sure your file is named exactly requirements.txt (all lowercase, no typos) and is placed in the root of your repository or in the same directory as your app’s entrypoint file.
