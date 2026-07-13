---
title: "St.time widget with bug"
url: "https://discuss.streamlit.io/t/st-time-widget-with-bug/121885#post_3"
date: "2026-07-10"
author: "@Laura3 Laura"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Hi Luigi, I looked into what might be causing your issue and I think it might be fixed by this change st.date_input calendar renders behind st.dialog overlay (regression in 1.59.0) · Issue #15859 · streamlit/streamlit · GitHub that was shipped in the 1.59.1 patch. Could you confirm if this fixes your issue? If not, could you submit an issue and include some more details like which version of Streamlit you are using, browser, and a reproducible code snippet?
