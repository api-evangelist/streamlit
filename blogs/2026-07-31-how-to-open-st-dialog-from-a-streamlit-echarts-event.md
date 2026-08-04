---
title: "How to open st.dialog from a streamlit-echarts event without full page rerun?"
url: "https://discuss.streamlit.io/t/how-to-open-st-dialog-from-a-streamlit-echarts-event-without-full-page-rerun/122087#post_5"
date: "2026-07-31"
author: "@Arvindra_Sehmi Arvindra Sehmi"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Andr8: if event and event.chart_event: show_dialog(event.chart_event) I’m suggesting putting this at the end of the script.
