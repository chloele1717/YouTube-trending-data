# YouTube-trending-data
The goal of this project is to analysed YouTube trending data from 11 countries by combining the data from various sources, stored in Microsoft  Azure storage and ingesting to Snowflake data Lakehouse.

YouTube, the renowned video-sharing platform, maintains a record of its most popular trending videos. To determine the year's top-trending videos, YouTube utilizes various factors, including user engagement metrics such as views, shares, comments, and likes, as reported by Variety magazine. The dataset encompasses several months, starting from August 12, 2020, and extending to the present day. It contains daily records of YouTube's trending videos and covers 11 regions: India, USA, Great Britain, Germany, Canada, France, Russia, Brazil, Mexico, South Korea, and Japan. Each region's data is stored in a separate file, with each file containing information about up to 200 trending videos per day. The dataset includes various details such as video title, channel title, publication time, views, likes, dislikes, and comment count. Additionally, there's a category_id field, which varies depending on the region.

A dataset with a daily record of the top trending YouTube videos has been extracted through the Youtube API and made available on the Kaggle (https://www.kaggle.com/rsrishav/youtube-trending-video-dataset)

