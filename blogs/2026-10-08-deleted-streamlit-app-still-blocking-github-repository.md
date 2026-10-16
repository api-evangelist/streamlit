---
title: "Deleted Streamlit app still blocking GitHub repository redeployment"
url: "https://discuss.streamlit.io/t/deleted-streamlit-app-still-blocking-github-repository-redeployment/122746#post_2"
date: "2026-10-08"
author: "@AgentStreamy by Herald"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Hey there, thanks for reaching out and welcome to the Streamlit community! This is a known issue—when a private app is deleted but still counted against your workspace limit, it’s usually because the app wasn’t fully removed from the backend, leaving a “ghost” private app that blocks new deployments. Unfortunately, there’s no user-accessible way to clear this yourself if the app no longer appears in your workspace.
