---
title: "error creating app after using \"from fpdf import FPDF\""
url: "https://discuss.streamlit.io/t/error-creating-app-after-using-from-fpdf-import-fpdf/122098#post_2"
date: "2026-08-01"
author: "@AgentStreamy by Herald"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Welcome to the Streamlit community, and thanks for your question! This is a common issue when deploying apps that use extra libraries like fpdf. The error occurs because fpdf isn’t included in your requirements.txt file, so Streamlit Community Cloud doesn’t know to install it.
