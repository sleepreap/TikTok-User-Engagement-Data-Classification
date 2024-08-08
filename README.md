# TikTok-User-Engagement-Data-Classification
 Building a machine learning model that can be used to determine whether a video contains a claim or whether it offers an opinion.

# Dataset Information

TikTok is the leading destination for short-form mobile video. The platform is built to help imaginations thrive. TikTok's mission is to create a place for inclusive, joyful, and authentic content–where people can safely discover, create, and connect.
This dataset is used to determine whether a video contains a claim or whether it offers an opinion.

Variable  |Description |
-----|-----|
#|TikTok assigned number for video with claim/opinion.|
claim_status|Whether the published video has been identified as an “opinion” or a “claim.” In this dataset, an “opinion” refers to an individual’s or group’s personal belief or thought. A “claim” refers to information that is either unsourced or from an unverified source.|
video_id|Random identifying number assigned to video upon publication on TikTok.|
video_duration_sec|How long the published video is measured in seconds.|
video_transcription_text|Transcribed text of the words spoken in the published video.|
verified_status|Indicates the status of the TikTok user who published the video in terms of their verification, either “verified” or “not verified.”|
author_ban_status|Indicates the status of the TikTok user who published the video in terms of their permissions: “active,” “under scrutiny,” or “banned.”|
video_view_count|The total number of times the published video has been viewed.|
video_like_count|The total number of times the published video has been liked by other users.|
video_share_count|The total number of times the published video has been shared by other users.|
video_download_count|The total number of times the published video has been downloaded by other users.|
video_comment_count|The total number of comments on the published video.|

**Download link:** [https://www.kaggle.com/mlg-ulb/creditcardfraud](https://www.kaggle.com/datasets/yakhyojon/tiktok/data)

# Libraries

- pandas
- matplotlib
- seaborn
- scikit-learn

# Algorithms

- Decision Tree
- Random Forest
- XGBoost
  
**Best Model AUC Score:** 99.80
