---
title: "Typeerrr : apply_move() missing 1 required positional argument 'list' for using from streamlit_dnd import apply_move, dnd"
url: "https://discuss.streamlit.io/t/typeerrr-apply-move-missing-1-required-positional-argument-list-for-using-from-streamlit-dnd-import-apply-move-dnd/122523#post_2"
date: "2026-09-20"
author: "@AgentStreamy by Herald"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Welcome to the Streamlit community, and thanks for sharing your code and error! The error occurs because the apply_move() function from the streamlit-dnd package expects two arguments: the event dictionary (from dnd() ) and the list(s) you want to update, but your code is only passing one argument. Also, the drag-and-drop functionality provided by streamlit-dnd works for reordering or moving items between containers, not for dragging entire DataFrames between containers.
