---
title: "Switching pages within the new st.column_config.ButtonColumn"
url: "https://discuss.streamlit.io/t/switching-pages-within-the-new-st-column-config-buttoncolumn/121910#post_4"
date: "2026-07-10"
author: "@Laura3 Laura"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Hi @Johan5 , The rerun will be required to switch the page, so currently I don’t see any workaround, unless maybe you do something like set the session state in the callback, and then later in the script outside of the callback use the session state value to trigger a switch_page. We are exploring a feature that would allow reruns within callbacks, however, see the spec I wrote. here: [spec] Event-scoped fragment reruns by sfc-gh-lwilby-1 · Pull Request #15755 · streamlit/streamlit · GitHub .
