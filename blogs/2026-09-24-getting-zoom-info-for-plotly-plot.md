---
title: "Getting zoom info for Plotly plot"
url: "https://discuss.streamlit.io/t/getting-zoom-info-for-plotly-plot/16368#post_3"
date: "2026-09-24"
author: "@Daniel96 Daniel"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
You can listen for the Plotly event and use the new x/y range to update your other component. If you’re using Dash, is probably the easiest way to trigger a callback whenever the user zooms or pans.
