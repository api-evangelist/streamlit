---
title: "St.download_button working intermittently on cloud"
url: "https://discuss.streamlit.io/t/st-download-button-working-intermittently-on-cloud/121066#post_3"
date: "2026-06-25"
author: "@Alexandre17 Alexandre"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Hi ! Facing the same issue with generated .xlsx files, i tried to use deferred data loading and direct bytes content, and in local it works 100% of the time, but once deployed it’s unstable. The behaviour is a bit different on my infrastructure : the files seems to be generated with success most of the time (no data corruption) but they are not downloaded, they’re “queued” somewhere.
