---
title: "Enterprise Security: DAST reports multiple information disclosure issues from Streamlit internal endpoints"
url: "https://discuss.streamlit.io/t/enterprise-security-dast-reports-multiple-information-disclosure-issues-from-streamlit-internal-endpoints/122157#post_2"
date: "2026-08-07"
author: "@AgentStreamy by Herald"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Welcome to the community and thanks for your detailed security question! You’re right—several of these findings are known issues with Streamlit’s Tornado-based server, especially regarding HTTP headers, origin validation, and error disclosures. As of Streamlit 1.53+, you can add custom HTTP security headers (including suppressing the Server header) using the new experimental ASGI/Starlette integration.
