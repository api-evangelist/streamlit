---
title: "New component: streamlit-arborist. Create interactive tree views"
url: "https://discuss.streamlit.io/t/new-component-streamlit-arborist-create-interactive-tree-views/119170#post_5"
date: "2026-07-20"
author: "@gabriel-msilva Gabriel Mello SIlva"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
I have released version 0.4.0 of streamlit-arborist which includes a new widget: tree_checkbox() pip install streamlit-arborist==0.4.0 tree_checkbox() displays a tree view with check boxes and cascading multi-selection. from streamlit_arborist import tree_checkbox data = [ { "id": "1", "name": "Parent 1", "children": [ {"id": "1.1", "name": "Child 1"}, {"id": "1.2", "name": "Child 2"} ] }, { "id": "2", "name": "Parent 2", "children": [ {"id": "2.1", "name": "Child 3"}, {"id": "2.2", "name": "Child 4"} ] } ] tree_checkbox(data, icons={"open": "📂", "closed": "📁", "leaf": "📄"})
