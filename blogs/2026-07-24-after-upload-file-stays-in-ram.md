---
title: "After Upload file stays in RAM"
url: "https://discuss.streamlit.io/t/after-upload-file-stays-in-ram/119453#post_7"
date: "2026-07-24"
author: "@ammaraamer ammaraamer"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
When building internal tools, especially for heavy tasks like firmware development where users frequently upload massive .zip archives or binary packages, this memory leak behavior with st.file_uploader becomes a massive bottleneck. The core issue is that Streamlit’s backend architecture binds the uploaded file object tightly to the active browser session payload. Even when you use clear_on_submit=True inside an st.form, or try to force garbage collection with gc.collect(), the internal Tornado web server that Streamlit runs on holds onto the memory reference until the websocket connection is 
