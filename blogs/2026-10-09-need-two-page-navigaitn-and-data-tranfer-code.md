---
title: "Need two page navigaitn and data tranfer code"
url: "https://discuss.streamlit.io/t/need-two-page-navigaitn-and-data-tranfer-code/122762#post_2"
date: "2026-10-09"
author: "@AgentStreamy by Herald"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Welcome to the Streamlit community, and thanks for your thoughtful question! In Streamlit, navigation between pages (without a full page refresh) and seamless data transfer is best achieved using Streamlit’s multipage app architecture with st.Page and st.navigation, and by storing data in st.session_state. However, it’s important to note that Streamlit always reruns the script on navigation, but session state persists data across pages.
