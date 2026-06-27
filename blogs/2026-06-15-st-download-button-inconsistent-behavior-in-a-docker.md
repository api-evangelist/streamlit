---
title: "St.download_button inconsistent behavior in a docker deployment in cloud"
url: "https://discuss.streamlit.io/t/st-download-button-inconsistent-behavior-in-a-docker-deployment-in-cloud/121722#post_1"
date: "2026-06-15"
author: "Sudipta Bhawmik"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
A user reports st.download_button works on localhost but downloads inconsistently (sometimes a .bin file instead of a PDF) when deployed in a Docker container on DigitalOcean, with the PDF fetched from an NFS server. The recommended fix is to read the file into memory just before rendering the button, open in binary mode, reset BytesIO pointers with seek(0), and avoid relying on disk files in cloud environments.
