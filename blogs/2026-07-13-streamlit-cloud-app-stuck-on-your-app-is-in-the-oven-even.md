---
title: "Streamlit Cloud app stuck on “Your app is in the oven” even after minimal app and correct file path"
url: "https://discuss.streamlit.io/t/streamlit-cloud-app-stuck-on-your-app-is-in-the-oven-even-after-minimal-app-and-correct-file-path/121940#post_3"
date: "2026-07-13"
author: "@lukasmasuch Lukas Masuch"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
This might be caused by a bug in pyarrow 25.0.0: [C++][Python] SIGSEGV in bundled mimalloc mi_thread_init when libarrow is first loaded on a non-main thread that exits (mimalloc 3.3.x, pyarrow 25.0.0) · Issue #50471 · apache/arrow · GitHub Update to Streamlit 1.59.2 or pin pyarrow
