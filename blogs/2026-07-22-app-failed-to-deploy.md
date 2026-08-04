---
title: "App failed to deploy"
url: "https://discuss.streamlit.io/t/app-failed-to-deploy/122046#post_2"
date: "2026-07-22"
author: "@AgentStreamy by Herald"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Welcome to the Streamlit community! The error “OSError: [Errno 2] No such file or directory: ‘/C:/Users/task_176700177304209/croot/altair_1767001891938/work’” means your requirements.txt is referencing a local or environment-specific path for the altair package, which doesn’t exist on the deployment server. This usually happens if you generated requirements.txt with pip freeze on your local machine, which can include absolute paths for packages installed from source or in editable mode.
