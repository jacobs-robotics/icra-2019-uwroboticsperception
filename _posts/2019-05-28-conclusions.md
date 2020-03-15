---
layout: post
title: Workshop conclusions
subtitle: Take-aways, ideas discussed and future directions
bigimg: "/img/uw_bg_1.jpg"
---

First of all, we would like to thank all the people who collaborated to the workshop one way or another -- presencially or remotely. All of your input served to have more productive discussions and to learn more about the state of the underwater robotics community. <ins>Approximately we had 40 participants during the event, 60 people registered for updates and online participation, and 1100 active website visitors (since March 1st until May 24th)</ins>.

![alt text](http://icra-2019-uwroboticsperception.ge.issia.cnr.it/assets/ws-pics/ws-pic-1-scaled.jpg "Workshop picture")

The objective of this section is to summarize, to the best of the organizers effort, the key discussions and thoughts that took place during the workshop among the audience and speakers.
With this, the reader and the research community can *hopefully* gain some insight on the current concerns, lines of thought, needs and future work in this exciting field of underwater robotics. If you wish to comment about this, to share your vision or ideas for collaboration, please feel free to do so using this [**online form**](https://forms.gle/rtstndaAr4cAtMH27) and we will display your comment at the end of this page.

It is important to mention that no thorough statistical or surveying methods were applied, what we offer is a qualitative review. Having said this, we want to emphasize the next points that were discussed during the workshop:

{: .box-warning}
**1. The underwater comunity urgently needs common reference datasets to validate, compare and contrast proposed methods.**

{: .box-warning}
**2. Although great advancements in sonar and 3D laser technology has been made, optical cameras are the main used sensor and necessary for end users.**

## 1. Baseline underwater datasets for the community

One of the topics that brought the most attention during the panel discussion, was **the need for baseline underwater datasets that the community can use to validate, compare and contrast proposed methods**. We stress the next observations:

1. Most participants concurred that in many cases each research group or company uses their own collected dataset to run experiments, due to the low availability of public samples, or lack of information about how these samples were acquired and sensors calibrated and set-up.

2. Some research groups have tried to publish their collected datasets, but they have not been received well by journals that usually make them available. The main reasons given is that the determination of ground truth values is not standarized or precise enough.

**Point #1** is due to several factors. First of all, the data collection campaigns underwater are expensive, specially if different environmental conditions need to be captured and many deployments required. They are risky as well, as accidents on the field generally mean the loss of the deployed system or costly hardware fixes. In consequence, this may cause a certain level of hesitation in sharing the datasets that took a great amount of logistics efforts and time to gather. Data acquisition is also performed in parallel to other experiments to save time, e.g., during navigation, communication, hardware tests, etc.; however, little attention is given to the set-up, calibration or environment conditions and these samples end up being used only in qualitative analysis.

**Point #2** has been the case for a couple of researchers on the field. The problem is that acquiring high precision ground truth data from underwater environments is arguably harder than for on-land robotics in many cases. For example, how to know the 'real' (underattenuated) colors of objects that have never been above water? Such as corals, archaelogy pieces, shipwrecks, etc. How to achieve the precision of body motion capture systems for divers? How to control or forecast turbidity in open waters to acquire enough samples for many turbidity levels that impact image quality? Depending on the application, there are many factors hard to control for the researchers, and for this reason perhaps underwater datasets should be evaluated under another set of criteria by peer-reviewed journals. 

Next, we mention a couple of suggestions from the community to address this issue which are still open-ended.

* **Industries/Companies should partner with researchers for the collection of public datasets to boost the state-of-the-art algorithms underwater.**

Well known datasets such as COCO and KITTI have been initiated by industry research centers such as Microsoft and Toyota respectively, and have been major stepping stones in the development of computer vision techniques in the last years. The underwater community would greatly benefit from such a dataset. From another perspective, researchers should also reflect on an application which captures the interest of the industry to sway them into collaboration; the "autonomous-driving" for underwater robotics in an exaggerated way of speaking.  

* **Focus efforts on a baseline simulation software to reduce the costs and uncertainties of field trials.**

Advancements on GPUs and related software that have enabled technologies such as ray tracing will eventually (soon?) allow scientists to simulate the broad variety of underwater light conditions. Perhaps a unified simulation software for the underwater community is a better and less expensive choice than the collection of data under highly variable and unpredictable settings. 

## 2. Constant need of optical-cameras

During the workshop, progress on the state-of-the-art techniques using aperture sonars and 3D RGB lasers were presented by [**Prof. Michael Kaess**](http://icra-2019-uwroboticsperception.ge.issia.cnr.it/assets/presentations/keynotes/MichaelKaess-ImaginingSonar.pdf "Kaess Presentation"), [**Dr. Narcis Palomeras**](http://icra-2019-uwroboticsperception.ge.issia.cnr.it/assets/presentations/keynotes/PereRidao-RealtimeLaserScanner.pdf "Ridao Presentation") and **Dr. Jakob Schwendner** during their presentations; which have proven to deliver high-quality mapping for inspection and monitoring tasks. Although these sensors are more expensive and arguably demand more complex calibration and set-up mechanisms, they are more robust against changes on the environments conditions, i.e., turbidity, lightening, etc., than optical cameras.

Nonetheless, we believe that the usage and importance of optical cameras will not diminish. Acoustic and laser based sensors undeniably provide more detailed information about the environment, but most end users such as farmers, marine biologists and archaeologists are not trained to interpret acoustic images or remain skeptical until confirmation from optical cameras is received, which usually is available much faster than 3D dense reconstructed maps. This was briefly discussed during our panel discussion and mentioned by **Dr. Erin Fischell** from WHOI while presenting her [**work**](http://icra-2019-uwroboticsperception.ge.issia.cnr.it/assets/presentations/spotlight/Fischell-Aquaculture.pdf "Fischell Presentation") on Autonomous Underwater Vehicles for aquaculture with kelp farmers. 

Likewise, through our open online survey it was observed that almost all users, approximately 20 research scientists, have an optical camera in their systems despite having other vision sensors available. The reasons for their usage may vary in this case: validation, monitoring, sensor-fusion, active sensing, among others; but the fact is that optical cameras remain a constant need. This can be one of the factors for the active and trending research in image enhancement, i.e., dehazing methods, as presented by [**Dr. Ayoung Kim**](http://icra-2019-uwroboticsperception.ge.issia.cnr.it/assets/presentations/keynotes/Kim-VisibilityEnhancementTurbidSLAM.pdf "Kim Presentation") and [**Dr. Katherine A. Skinner**](http://icra-2019-uwroboticsperception.ge.issia.cnr.it/assets/presentations/keynotes/Skinner-UnsupervisedLearningUWImageRestoration.pdf "Skinner Presentation"). For these reasons, we believe research will and should continue to improve underwater imagery under many different environmental conditions for their better exploitation among researchers and data consumers; and to push the use of the algorithms already developed for on-land robotics.   

![alt text](http://icra-2019-uwroboticsperception.ge.issia.cnr.it/assets/conclusions/sensors_chart.png "Sensors Survey")

#### COMMENTS

Comming soon. 












