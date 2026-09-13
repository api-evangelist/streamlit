---
title: "WebSocket upgrade handshake broken on Community Cloud — HTTP 502 on external client, and session cookies not surviving reload in-app (post Debian bullseye-security incident)"
url: "https://discuss.streamlit.io/t/websocket-upgrade-handshake-broken-on-community-cloud-http-502-on-external-client-and-session-cookies-not-surviving-reload-in-app-post-debian-bullseye-security-incident/122449#post_5"
date: "2026-09-11"
author: "@raethlein Benjamin Raethlein"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
@restautelmarbella For 2: runtime.txt is ignored by Community Cloud. You can change the Python version in the “Advanced Settings” dialog of an app. For 3: I am surprised that setting a custom cookie worked at all.
