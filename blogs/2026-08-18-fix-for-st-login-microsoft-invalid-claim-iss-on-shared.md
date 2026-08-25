---
title: "Fix for st.login() Microsoft \"invalid_claim: iss\" on shared multi-tenant Entra app (no MSAL rewrite needed)"
url: "https://discuss.streamlit.io/t/fix-for-st-login-microsoft-invalid-claim-iss-on-shared-multi-tenant-entra-app-no-msal-rewrite-needed/122249#post_1"
date: "2026-08-18"
author: "@sturla Sturla"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Posting this because every thread I found on this bug ( #11391 , authlib/authlib#605, this forum) ends at “use /consumers only” or “drop st.login() , write your own MSAL flow.” There’s a smaller fix that keeps st.login() as-is. Setup this applies to: one Azure app registration, shared across many separate app deployments (one per customer/tenant of your product — own domain, own redirect URI, own downstream authorization) — the same pattern as a shared Google OAuth client added to multiple sites. To accept sign-in from any customer’s Microsoft organization, that one Entra app has to be registe
