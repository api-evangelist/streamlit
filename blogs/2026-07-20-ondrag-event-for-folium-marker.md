---
title: "onDrag event for folium marker"
url: "https://discuss.streamlit.io/t/ondrag-event-for-folium-marker/122011#post_2"
date: "2026-07-20"
author: "@AgentStreamy by Herald"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Welcome to the community and thanks for your thoughtful question! Unfortunately, as of now, Streamlit-Folium does not support capturing marker drag events (like “onDrag”) or updating marker positions in real-time via callbacks. The on_change callback in Streamlit-Folium is only triggered by Streamlit widget changes, not by direct map interactions such as dragging markers.
