---
title: "Geospatial Indexing with H3 & S2 — Two Apps + a New Component (streamlit-hexviz)"
url: "https://discuss.streamlit.io/t/geospatial-indexing-with-h3-s2-two-apps-a-new-component-streamlit-hexviz/121440#post_2"
date: "2026-07-31"
author: "@Robert35 Robert"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Hey again Happy to share that the new version 0.2.0 is available now. The optional import of A5 ( https://a5geo.org/ ) is now introduced. Example on earthquakes import pandas as pd import streamlit_hexviz as shv data = pd.read_csv('data/all_month.csv') shv.a5_map(df=data, lat='latitude', lon='longitude', use_sidebar_controls=True) The sidebar controls is a native streamlit option and enables the switch between resolutions, change of color scheme.
