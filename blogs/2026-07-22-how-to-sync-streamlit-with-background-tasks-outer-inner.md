---
title: "How to sync Streamlit with background tasks: Outer/Inner caching"
url: "https://discuss.streamlit.io/t/how-to-sync-streamlit-with-background-tasks-outer-inner-caching/122025#post_3"
date: "2026-07-22"
author: "@Angela1 Angela"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Hi! unfortunately it does not work as expected … the only way I could have it updated is to set a refresh .. for now it is set every 15 minutes # Refresh every 15 minutes * 60 seconds * 1000 milliseconds = 900000 st_autorefresh(interval=15 * 60 * 1000, key="quarter_hour_heartbeat") Maybe it is not the ideal solution but it is a sort of workaround.
