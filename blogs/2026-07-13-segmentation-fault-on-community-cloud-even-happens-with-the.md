---
title: "Segmentation fault on Community Cloud — even happens with the default/starter template, not just my app"
url: "https://discuss.streamlit.io/t/segmentation-fault-on-community-cloud-even-happens-with-the-default-starter-template-not-just-my-app/121945#post_3"
date: "2026-07-13"
author: "@lukasmasuch Lukas Masuch"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
This is most likely be caused by a bug in pyarrow 25.0.0: [C++][Python] SIGSEGV in bundled mimalloc mi_thread_init when libarrow is first loaded on a non-main thread that exits (mimalloc 3.3.x, pyarrow 25.0.0) · Issue #50471 · apache/arrow · GitHub Please make sure to update to Streamlit 1.59.2 or pin pyarrow
