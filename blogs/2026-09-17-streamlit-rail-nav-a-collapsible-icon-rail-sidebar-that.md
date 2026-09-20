---
title: "Streamlit-rail-nav: a collapsible icon-rail sidebar that expands on hover — no iframe, no frontend build"
url: "https://discuss.streamlit.io/t/streamlit-rail-nav-a-collapsible-icon-rail-sidebar-that-expands-on-hover-no-iframe-no-frontend-build/122495#post_1"
date: "2026-09-17"
author: "@ai11 Bernhard"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Hey everyone, I’m excited to share streamlit-rail-nav : a configurable icon-rail sidebar for Streamlit apps. The sidebar collapses down to a thin strip of icons and smoothly expands into a full labeled menu on hover — the pattern you see in a lot of modern SaaS dashboards. Demo Live demo → GitHub repo github.com/aizech/streamlit-rail-nav PyPI streamlit-rail-nav · PyPI Installation pip install streamlit-rail-nav Quick start import streamlit as st from streamlit_rail_nav import render st.set_page_config(layout="wide", initial_sidebar_state="expanded") render({ "items": [ {"kind": "link", "label"
