---
title: "Streamlit Cloud apt deps failing + OpenCV import errors (libGL / libgthread)"
url: "https://discuss.streamlit.io/t/streamlit-cloud-apt-deps-failing-opencv-import-errors-libgl-libgthread/121648#post_3"
date: "2026-06-07"
author: "@Omer4 Omer"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
AgentStreamy: Welcome to the Streamlit community and thanks for the detailed info! You’re running into a common deployment issue: ImportError for libGL.so.1 and libgthread-2.0.so.0, and apt dependency failures for libglib2.0-0 due to missing libffi7 and libpcre3. This is because Streamlit Community Cloud uses Debian Bullseye, which doesn’t provide libffi7 or libpcre3 anymore, so installing libglib2.0-0 fails and breaks your dependency chain.
