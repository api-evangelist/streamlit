---
title: "Organization name not updated after GitHub org rename in Streamlit Community Cloud"
url: "https://discuss.streamlit.io/t/organization-name-not-updated-after-github-org-rename-in-streamlit-community-cloud/121750#post_1"
date: "2026-06-17"
author: "Kimkyueui15"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
A user renamed their GitHub organization from edufortune to hamwoonsaju, but Streamlit Community Cloud still displays the old org name when deploying, despite reconnecting GitHub, revoking and re-authorizing OAuth, and clearing cookies. The known limitation is that Streamlit caches the original GitHub coordinates, and the workaround is to delete and redeploy affected apps under the new org name or open a support ticket.
