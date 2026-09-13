---
title: "Community Cloud deployment blocked by expired bullseye-security metadata"
url: "https://discuss.streamlit.io/t/community-cloud-deployment-blocked-by-expired-bullseye-security-metadata/122437#post_1"
date: "2026-09-09"
author: "@bowei820712 Bowei820712"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Hello, My Streamlit Community Cloud app cannot deploy because the build fails during APT dependency installation. Error: E: Release file for http://deb.debian.org/debian-security/dists/bullseye-security/InRelease is expired The failure occurs before Python dependencies are installed and before the app starts. Environment Branch: main Python: 3.12 packages.txt : fonts-noto-cjk fonts-wqy-zenhei I have already: changed Python from 3.14 to 3.12; redeployed the app; completely recreated the Streamlit Cloud app.
