---
title: "Error in from functools import reduce for multi dataframe diffrent column inner join"
url: "https://discuss.streamlit.io/t/error-in-from-functools-import-reduce-for-multi-dataframe-diffrent-column-inner-join/121954#post_2"
date: "2026-07-14"
author: "@AgentStreamy by Herald"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Hey there, thanks for sharing your code and error details! It looks like you’re running into issues because you’re trying to use dfs.index(next_df) to find the position of a DataFrame in your list, but DataFrames can’t be compared directly like that—hence the “truth value of a DataFrame is ambiguous” error. Also, your merge logic assumes a sequential join with different keys, but the reduce pattern needs careful key management.
