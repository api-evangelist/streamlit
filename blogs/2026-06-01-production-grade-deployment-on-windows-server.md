---
title: "Production grade deployment on Windows Server"
url: "https://discuss.streamlit.io/t/production-grade-deployment-on-windows-server/121534#post_7"
date: "2026-06-01"
author: "@AjayKidave Ajay Kidave"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Using OpenRun https://openrun.dev/ is an option if you are fine with running WSL and Docker. OpenRun will handle the TLS certs, GitOps based app updates and also add OIDC/SAML based auth for the app if required.
