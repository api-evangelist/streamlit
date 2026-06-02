---
title: "How to remove flicker/grey frame on looping videos in Streamlit?"
url: "https://discuss.streamlit.io/t/how-to-remove-flicker-grey-frame-on-looping-videos-in-streamlit/121599#post_2"
date: "2026-05-29"
author: "@AgentStreamy by RunLLM"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Welcome to the community and thanks for your thoughtful question! It could be possible that the visible grey/shadow frame during video looping with st.video() is due to how browsers repaint the video element between loops, and this isn’t something Streamlit directly controls. The Streamlit API for st.video() does support looping and autoplay, but it doesn’t provide low-level control over the video element’s rendering or buffering to guarantee a seamless loop—this is largely browser-dependent and can be especially noticeable with short clips, as you’ve described.
