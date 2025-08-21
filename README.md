# YouTube Data Analysis

## Overview
- **Goal**: Analyze trending YouTube videos to understand engagement dynamics (views, likes, comments), category performance, and the impact of video duration and tags.
- **Stack**: Python, Pandas, Seaborn/Matplotlib, Jupyter.
- **Data**: Sample of trending videos with metadata and engagement metrics.

## Key Findings
1. **Strong correlations** between views, likes, and comments.
2. **Category insights**: Gaming, Entertainment, Sports, and Music dominate trending volume; categories like Music and People & Blogs score high on average engagement.
3. **Duration matters**: Shorter videos (0–5 minutes) tend to outperform longer videos on views and engagement.
4. **Tags**: The number of tags shows a very weak relationship with view counts; quality over quantity.
5. **Time-of-day**: Publishing distribution is skewed to 14:00–20:00; publish hour shows minimal impact on view count in this sample.

## Notable Visuals
- Correlation heatmap of views/likes/comments.
- Category bar charts: counts and average engagement.
- Duration-range engagement comparison.
- Engagement rate charts (likes per view) by category.
- Publish hour distribution and scatter vs view count.

## Reproducibility
- Notebook: `notebook/model.ipynb`
- Data path is relative: `../data/trending_videos.csv`
- No API key required; a static category mapping is used in the notebook.

## How to Run
1. Create a Python environment and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Open `notebook/model.ipynb` and run all cells.

