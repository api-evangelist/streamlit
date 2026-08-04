---
title: "Streamlit-coco — bring Snowflake CoCo (Cortex Code agent) into your Streamlit app 🐣"
url: "https://discuss.streamlit.io/t/streamlit-coco-bring-snowflake-coco-cortex-code-agent-into-your-streamlit-app/122072#post_1"
date: "2026-07-28"
author: "@Laurent2 Laurent"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Hey folks Quick share: I built a little component to drop Snowflake’s CoCo / Cortex Code agent straight into a Streamlit app. panel() streams the agent transcript across reruns tool calls (Glob, Grep, Read, Write, SQL, AskUser…) render as readable cards instead of raw JSON Write / Edit / Bash / SQL pause for a human Approve once / Always allow / Deny plus a headless query() for scripts & CI pip install "streamlit-coco[sdk]" Full honesty: it’s 0.1.0 , alpha, and 100% vibe-coded — the API may still move and there are rough edges. Sharing it early because it might be useful to someone, and I’d lo
