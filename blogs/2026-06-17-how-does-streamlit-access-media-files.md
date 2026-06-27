---
title: "How does streamlit access media files?"
url: "https://discuss.streamlit.io/t/how-does-streamlit-access-media-files/121742#post_1"
date: "2026-06-17"
author: "Sudipta Bhawmik"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
A user reports that clicking st.download_button on a cloud-deployed app logs a 200 GET on the internal /media/ path but the browser download fails with a 404 error, intermittently. The recommended fix is to read the file fully into memory as bytes (or use io.BytesIO with seek(0)) before rendering the download button and to avoid relying on files written to disk in cloud environments.
