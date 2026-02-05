# War of the Viz – Spotify Streaming Analysis

This repository contains my submission for **War of the Viz**, based on the *Most Streamed Spotify Songs 2024* dataset from Kaggle.

The goal of this visualization is to examine whether Spotify’s internal performance metrics such as **Spotify Popularity** and **Track Score** are sufficient to explain which songs become streaming mega-hits.

## Visualization Overview
- Each point represents a song.
- **X-axis:** Spotify Popularity score.
- **Y-axis:** Track Score (Spotify’s composite engagement metric).
- **Bubble size:** Log-scaled Spotify Streams, representing cumulative listening volume.
- **Color:** Explicit vs. non-explicit tracks.

Log scaling is applied to streaming counts to handle the highly skewed distribution of streams and to preserve relative differences between songs.

## Key Inferences
- Most songs cluster around moderate popularity and track scores, indicating a common performance range for mainstream releases.
- While higher Spotify Popularity and Track Scores are generally associated with higher streams, the most-streamed songs often appear as outliers rather than simply the highest-scored tracks.
- This suggests that Spotify’s internal metrics are informative but do not fully explain extreme streaming success.
- Explicit tracks show greater variance in performance, producing both some of the largest streaming hits and many lower-performing tracks.

## Conclusion
The visualization highlights that platform-level metrics alone are not sufficient to fully account for streaming mega-hits. Extreme success likely depends on additional factors beyond Spotify’s internal scoring signals, such as external exposure or long-term listener behavior.

## Contents
- `visualization.ipynb`: Final analysis and visualization notebook

## Dataset
Dataset source: Kaggle – *Most Streamed Spotify Songs 2024*
