# Instagram Engagement Analysis

## Question
What factors most strongly predict likes on Instagram posts,
and what does this mean for creators trying to grow?

## Dataset
Instagram Reach Analysis dataset from Kaggle — 100 posts across
accounts ranging from 11 to 4,496 followers.

## Key Findings

1. **Small accounts dramatically outperform large ones on engagement rate.**
   Accounts with under 100 followers averaged 66.2% engagement rate
   vs only 3.4% for accounts with 1K–5K followers — a 19x difference.

2. **Follower count is a surprisingly weak predictor of likes.**
   Correlation between followers and likes is only 0.27, meaning
   having more followers does not translate proportionally into more likes.
   Audience quality matters more than audience size.

3. **Time since posting is the strongest predictor of likes (r = 0.61).**
   Older posts consistently accumulate more likes than newer ones,
   suggesting consistency over time compounds more than any single
   post's timing or content strategy.

4. **Caption length has zero effect on likes (r = -0.015).**
   There is essentially no relationship between how long a caption is
   and how many likes a post receives.

## Insight for Creators
Stop optimising for follower count — optimise for engagement rate instead.
A loyal audience of 500 who interact with every post is worth more
algorithmically than 5,000 passive followers. Post consistently over
months rather than chasing a single viral moment; the data shows that
like accumulation over time is the strongest signal in this dataset.
Spend less time writing elaborate captions and more time on content quality.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Charts
![Engagement Rate by Follower Tier](chart1_engagement_by_tier.png)
![Followers vs Likes Scatter](chart2_followers_vs_likes.png)
![Time Since Posting vs Likes](chart3_time_vs_likes.png)
