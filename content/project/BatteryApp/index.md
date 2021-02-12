---
title: Thesis
summary: Data Collection and Analysis of Energy Consumption of Mobile Phones using Machine Learning Techniques
tags:
- battery
- battery monitor
- battery information
- BatterAapp
- smartphone usage
- energy drain prediction
- machine learning
- xgboost
- thesis
- python
date: "2016-04-27T00:00:00Z"

image:
  caption: BatteryApp system architecture
  focal_point: Smart

url_code: "https://github.com/mpalaourg/Thesis"
url_pdf: "media/thesis.pdf"
url_slides: "media/thesis.pptx"
url_video: ""
---

<div style="text-align: justify"> <p>
In a modern-day society there is the consensus that smartphones have a dominant role in everyday life. By just pressing a button, someone can not only get up to speed with the current events on a global scale, but also get in touch with people all over the world and find various forms of entertainment. In particular, one of the features that makes smartphones so attractive is the portability they offer, since they utilize batteries. However, batteries have a certain amount of charges in their disposal, consequently the lifespan of a device is directly correlated to its utilization, as well as its charging strategy.

The current thesis focuses on the analysis of mobile phones’ usage and the prediction of the battery’s energy drain. To begin with, for data collection the application [BatteryApp](https://play.google.com/store/apps/details?id=gr.auth.ee.issel.batteryapp), which periodically keeps record of the device’s usage and the battery information, was developed. The next step is the grouping of similar uses of devices through Hierarchical Clustering, which does not require an a priori selection for a specific cluster number and does not set limitations regarding the chosen distance function. After that, it was assessed based on its content in order to select the clusters with the higher information value. Lastly, the prediction of the energy drain was constructed by employing a simple linear model, two variants of linear regression, where the penalty concept is introduced (Ridge and Lasso Regression), and a non-linear model, which belongs to the Ensemble Learning category (eXtreme Gradient Boosted trees), with the parameters’ learning procedure being applied to each selected cluster individually.
</p> </div>

## **App Description**

<div style="text-align: justify"> <p>
As part of my Thesis, I have developed the Android application BatteryApp, which during its operation collects data from the mobile phone’s usage and the battery status at regular intervals. The data collected is anonymous, as during the installation of the app you will be assigned a unique user code. The information collected is:
</p> </div>

- The unique ID that distinguishes you from other users.
- The level, temperature, voltage, technology, status (charge/discharge), health (good/overheating) of the battery.
- CPU usage.
- If WiFi, Cellular Data, Bluetooth, Hotspot, GPS [^1] of the mobile are activated.
- The available RAM.
- The screen brightness level.
- If the phone is interactive (Screen is turned on or off).
- Sampling frequency.
- The model of the mobile and the android version.
- The percentage remaining in the battery capacity.
- The Timestamp of each sample.
[^1]: *Only if it is enabled, your location will NOT be logged.*

## **App usage**

<div style="text-align: justify"> <p>
BatteryApp <b>does not work</b> in the background, it collects data only when you activate it and there will be a notification in the Notification Shade the whole time you are using the app. To start a usage Session, open BatteryApp (e.g before you open YouTube or Instagram) and press the <u>START SESSION</u> button, with which BatteryApp will be minimized and data collection will begin. If you check your Notification Shade you should see a notification. To end the usage Session, return to BatteryApp and press the <u>END SESSION</u> button. The usage Sessions do not have to be long in duration, however, in the context of my Thesis, where the use of the battery is the main thing analyzed, the battery level must drop by at least 1% in each session in order to be of a greater value in the analysis. Finally, use the <u>Upload Button</u> to upload the files; uploading is not required after each use, as the Sessions are stored on the mobile and will be deleted after a successful upload.
<ul>
<li> You can change the sampling frequency (default is 1 sample every 10 seconds), at the number input box and via the <u>SUBMIT</u> button. </li>
<li> Files are uploaded by default only via WiFi. To upload while using Cellular data, you have to toggle the switch on the lower right corner. <i>File size for a 30-minute usage Session is: ~228kB (sampling every 5 seconds), ~114kB (sampling every 10 seconds)</i>. </li> 
</ul>
</p> </div>
