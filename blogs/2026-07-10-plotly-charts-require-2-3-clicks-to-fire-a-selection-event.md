---
title: "Plotly charts require 2-3 clicks to fire a selection event"
url: "https://discuss.streamlit.io/t/plotly-charts-require-2-3-clicks-to-fire-a-selection-event/121914#post_3"
date: "2026-07-10"
author: "@Davide4 Davide"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Hi, I understand the approach, but it won’t work in practice. You filter the dataframe at the end, once all charts have already been created. Then at each rerun, df_filtered = df.copy() copies the source dataframe, as if no filters were ever applied.
