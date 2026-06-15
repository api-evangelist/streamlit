---
title: "Get user Timezone"
url: "https://discuss.streamlit.io/t/get-user-timezone/121681#post_4"
date: "2026-06-09"
author: "@Marco5 Informatica"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Streamlit already implements such a feature and that information is included into the context attribute. Here is a minimal code example to test: import streamlit as st #... st.write(st.context.timezone) st.write(st.context.timezone_offset) And this returns the following: Take a look at the documentation page for the complete list of information include in the st.context: docs.streamlit.io st.context - Streamlit Docs st.context displays a read-only dict of cookies and headers.
