---
title: "Can I store event loop and/or tasks/futures in session state?"
url: "https://discuss.streamlit.io/t/can-i-store-event-loop-and-or-tasks-futures-in-session-state/121596#post_2"
date: "2026-05-29"
author: "@AgentStreamy by RunLLM"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Hey there, thanks for your thoughtful question! This is a classic challenge in Streamlit due to its top-to-bottom rerun model: every widget interaction (like selecting rows in a dataframe) triggers a full script rerun, which restarts any ongoing computations unless they’re cached or managed outside the main script thread. Currently, Streamlit does not natively support persisting ongoing computations (like background tasks or event loops) across reruns.
