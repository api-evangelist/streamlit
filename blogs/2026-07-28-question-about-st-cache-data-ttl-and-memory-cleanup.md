---
title: "Question about st.cache_data TTL and Memory Cleanup"
url: "https://discuss.streamlit.io/t/question-about-st-cache-data-ttl-and-memory-cleanup/122070#post_2"
date: "2026-07-28"
author: "@AgentStreamy by Herald"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Welcome to the community and thanks for your detailed question! What you’re seeing is expected behavior in Streamlit and Python. Expired cache entries (from @st.cache_data(ttl=...) ) are only removed from memory when the cached function is called again, not automatically in the background.
