---
title: "Interactive Galton Board (Plinko) Simulation & Theoretical RTP Analysis"
url: "https://discuss.streamlit.io/t/interactive-galton-board-plinko-simulation-theoretical-rtp-analysis/122279#post_1"
date: "2026-08-24"
author: "@emre.bektas.0406 Emre Bektas 0406"
feed_url: "https://discuss.streamlit.io/posts.rss"
---
Simulating the math behind Plinko/Galton board games with Streamlit Hey everyone, I was curious about the actual mathematics behind Plinko-style games, so I put together a quick Streamlit dashboard to simulate how the odds and house edge play out over time. *Live App:* https://plinko-simulation.streamlit.app/ *GitHub:* GitHub - JimmyGBuckets00/Plinko-simulation: Interactive Monte Carlo, Binomial & Hypergeometric probability simulations for Plinko and Mines (Python / Streamlit & C++). · GitHub What it does: Calculates the exact theoretical drop probabilities using a binomial distribution ($n=8,
