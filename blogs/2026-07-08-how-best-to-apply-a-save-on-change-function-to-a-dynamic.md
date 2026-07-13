---
title: "How best to apply a save on_change function to a dynamic filter?"
url: "https://discuss.streamlit.io/t/how-best-to-apply-a-save-on-change-function-to-a-dynamic-filter/121887#post_3"
date: "2026-07-08"
author: "@will.stock Will Stock"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
One small update, I did some extra research and discovered that using the below code for applying changes prevents the filters from overwriting the entire df. def save_edits(): merged_df = pd.merge(st.session_state.df1,st.session_state.edited_df1,how='outer',indicator=True) diff_df1 = merged_df[merged_df['_merge'] == 'right_only'] if len(diff_df1)>0: df1.update(st.session_state.edited_df1 Streamy’s suggestions to “use a callback” or “commit changes immediately after editing” is pretty much what I’m trying to do. A “Save changes” button doesn’t help if all the changes were removed when a new fi
