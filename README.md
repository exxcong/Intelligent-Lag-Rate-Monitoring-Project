# Intelligent-Lag-Rate-Monitoring-Project
Intelligent Lag Rate Monitoring Project Suitable for Video Company



* **Project Name:** Intelligent Lag Rate Monitoring Project Suitable for Video Company



* **Project Background:** User viewing experience is the lifeline of a video company, and playing lag is the number one killer affecting user experience. Users may watch choppy videos when using our products. As a data analyst, we should monitor the data of lag rate and other core indicators, use the anomaly detection algorithm to automatically find abnormal points, intelligently analyze the causes based on the root cause analysis algorithm, and form a daily intelligent monitoring report email, so as to escort the lifeline of the company.




* **Goal:** Design an intelligent Lag Rate Monitoring system which can achieve automatically fetch data from MySQL everyday, and judge whether the Lag Rate of the day is abnormal. If the value is normal, then perform routine analysis, analysizing Lag Rate from different dimensions, like calculating Lag Rate of different CDN providers and visualizing them accordingly. If the value is abnormal, then use root cause analysis algorithm to further position causes and output abnormality analysis report. Finally, form a complete analysis daily report and send through email.




* **Column Description:** 
* user_plat: what system user is using, like ios or android
* cdn_name: CDN(Content Delivery Network) providers.
* CDN is a geographically distributed network of proxy servers and their data centers. The goal is to provide high availability and performance by distributing the service spatially relative to end users.
* roomid: id of video
* province: province of user
* isp: the operator of user
* lag_people: Total number of users with lag problem in the day
* all_people: Total number of users in the day

* Lag Rate: key indicator = lag_people / all_people 
* For example, if Lag Rate in 2021-01-03 is 5%, it means 5 out of every 100 users that day have watched choppy videos.
