# Youtube Channel Analysis

**This Process on this Project.**

![image](https://user-images.githubusercontent.com/113614347/225645157-ae69658b-c122-4a45-8332-f3ac344835ad.png)


> **CONTENT**


> **IDEAS**

The analysis context comes from the idea of how beauty topics are on the YouTube video platform. Definition of the content of which products are trending. Starting from that, I conducted a project to analyze some famous beauty bloggers in Vietnam.

>**SCRAPPING DATA**

`Step 1` Setup environment and API.

`Step 2` Get ChannelID of channels that I want to analyze.

In this Project I chose some famous beauty blogger like: `#Chang Makeup`, `#Chloe Nguyen`, `#Happy Skin VN`, `#Linh Truong`, `#Mai Van Trang`, `#Quynh Anh Shyn`, `#Trinh Pham`

`Step 3` Scrapping and Preprocessing raw data.

`Step 4` Extract data to CSV file.

For more detail about the Python code I used to scrapping. Please contact me via: lvcuong2801@gmail.com

>**LOAD CSV file to PowerBI**

You can see in the dataset that the data ranges from 11 April 2010 to 14 March 2023. Because it is a large time range, I created a slicer to filter for the dashboard. 

![image](https://user-images.githubusercontent.com/113614347/225662103-0ce3b8b7-f5c2-4079-a526-be1cc6e53eca.png)

I also create a slicer about Channel that you can filter when needed

![image](https://user-images.githubusercontent.com/113614347/225662296-2efa763e-0265-4bca-a30f-4f55dcc0a6f8.png)

Another Slicer is TOP N, the purpose is to filter TOP (5, 10, 15) some feature in the charts.

![image](https://user-images.githubusercontent.com/113614347/225662529-a27b0c2d-53a8-45dc-9fb0-985b9ff352e6.png)

>> **`View per video`**

![image](https://user-images.githubusercontent.com/113614347/225663451-2c2a09d7-2d93-4ac0-92d8-a6d551d716fb.png)

Firstly, let me tell you the current status of our beauty bloggers.
`Chang makeup` has produced some interesting videos. This helped them to achieve the highest average views per video.
Meanwhile, the rest also produced many million-view videos but they didn't get audience attention, the average video per video declined.

>>**Views per Minute**

`Chang Makeup` continues to be in first position in the view per minute. Next, `Quynh Anh Shyn`’s Views per Minute rank the second despite their video not having as many views as `Chang Makeup` or the others.

>> **View Count and Top 10 View Count by Year**

This metric answer for the question: "How have the views on each channel changed over the years?"
We'll go into details for each Channel.

***Chang Makeup***
![image](https://user-images.githubusercontent.com/113614347/225673137-015e7213-6f37-44c2-9449-12ffd8fad869.png)

She had the highest number of views in 2016 then decreased in 2018. 2019 had a slight increase in views. However, the number of views then began to decrease gradually. The reason is that she is pregnant and starting to take care of the baby, so she doesn't have as much time to post videos as before.

***Chloe Nguyen***

![image](https://user-images.githubusercontent.com/113614347/225673378-14350314-2e7a-4a11-a84c-ead2f3f963b9.png)

`Chloe Nguyen` is also a famous beauty blogger, the number of views on the channel remains stable. There was a decline in interaction in two periods, 2017-2019 and 2021-present.

***Happy Skin***

![image](https://user-images.githubusercontent.com/113614347/225680020-2c559d2d-62ad-4958-a2b2-ce8efa959c93.png)

`Happy skin` has a view like a pyramid. The highest viewing peak in 2018 with a total of 31.4M views. However, the closer to the two sides, the more the decline in views. We can dig deeper into why there's been an interesting decline like this by using data mining techniques.


***Linh Truong***

![image](https://user-images.githubusercontent.com/113614347/225682193-f5f6297e-bb35-4fb4-b0ed-daf598ec4f41.png)

`Linh Truong` does not have as many views as other channels, but maintains a stable performance. However, 2022 saw a significant decline in views. If she wants to grow, she needs to find out what video content causes to break through again.


***Mai Van Trang***

![image](https://user-images.githubusercontent.com/113614347/225683081-2fdad390-8067-41d0-9611-99a3e284cb33.png)

Similarly, `Mai Van Trang`'s channel has the same trend as `Linh Truong`'s channel

***Quynh Anh Shyn***

![image](https://user-images.githubusercontent.com/113614347/225683827-68aeaf7a-4b46-4f59-90b4-07c67ab02c8a.png)

From 2017, `Quynh Anh Shyn`'s performance is not as good as before. Her views are decreasing, maybe the reason is because she changed direction from beauty blogger to fashion industry.

***Trinh Pham***

![image](https://user-images.githubusercontent.com/113614347/225683925-ac421651-c838-4372-89c0-73c13e98d1df.png)

`Trinh Pham` no longer seems to be able to create as many videos that attract viewers as before. The period from 2020 to now has witnessed a significant decrease in the channel's views.

**The chart below is answering for "What kind of content did audience want to watch most?"**

>>**TOP N (5, 10, 15) HIGHEST COMMMENT + LIKE VIDEOS OF EACH CHANNEL**


![image](https://user-images.githubusercontent.com/113614347/225686412-d01bba49-367f-4da5-823d-a9073dd1e2c0.png)
![image](https://user-images.githubusercontent.com/113614347/225686541-1bc23c42-9caf-4624-9579-5ca3e1adddfc.png)
![image](https://user-images.githubusercontent.com/113614347/225686604-54f4cfa0-4e86-4da4-bb36-64dcc9ff97aa.png)

>>**TOP N (5,10, 15) HIGHEST VIEW VIDEOS OF EACH CHANNEL**

![image](https://user-images.githubusercontent.com/113614347/225687606-7c38e45c-705c-427f-9c87-bb588f8d7b47.png)
![image](https://user-images.githubusercontent.com/113614347/225687746-c283beb3-d506-460d-ab89-0762cc9ab0fa.png)
![image](https://user-images.githubusercontent.com/113614347/225687819-8d9e5e64-32e3-4f9d-97ce-a704b2c3d2aa.png)

> **FOR FUTURE ANALYSIS - CONCLUSION**

Currently, this report is only done at the stage of general descriptive analysis of channels. I suggest you can do some data mining techniques such as extracting topics from video content, analyzing the sentiment of comments in each video. Besides, the analysis also has the limitation that it only collects data for big and old youtubers, those who are famous recently have not. Readers can enrich these limitations to enrich the analysis.

