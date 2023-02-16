---
title: 'About'
date: 2018-02-22T17:01:34+07:00
layout: page
bodyClass: page-about
---

Cue Band was devised by a group of researchers and funded with a grant of £198,571.52 from Parkinson's UK. Cue Band aims to develop a new wearable to significally reduce the drooling symptoms through cueing for people with Parkinson's.


## About Drooling in Parkinson's

Sialorrhoea, also termed drooling or ptyalism, is a common symptom of Parkinson's, affecting up to 80% of people. Drooling can be a significant problem for people with Parkinson's due to decreased automatic swallowing. Mainly when people are multi-tasking and concentrating on other things such as watching television. When automatic swallows don't occur, saliva pools in the mouth, leading to drooling, which can be very embarrassing, restricting the social life of people with Parkinson's.
The current treatments to tackle drooling focus on decreasing saliva production. Either with oral agents, such as glycopyrronium, or via Botox injections into the salivary gland, which must be repeated on a 3-monthly basis.  These treatments are problematic, as it is well known that saliva is essential for good oral health. Impaired production or loss of saliva through drooling exposes individuals to a range of adverse effects, including significant health and psychosocial issues.

* [More information about drooling](https://www.parkinsons.org.uk/information-and-support/eating-swallowing-and-saliva-control)


<h2 id="about-technology"> Technology behind Cue Band </h2>
<h3 id="about-wearable"> The Wearable Wristband - Cue Band </h3>
Cue Band is a small wearable device worn on the wrist, allowing discrete and comfortable wear. It allows individuals to define a 7-day cueing schedule of when the device should start/stop cueing, as well as modify the intervals and intensity of the haptic cues. 

The Cue Band hardware is the [PINE64 PineTime Smartwatch](https://wiki.pine64.org/wiki/PineTime). This hardware was chosen as its design is open source and it allows us to use our own custom firmware to customize the device's behaviour. The firmware is a custom "fork" off the [InfiniTime open source firmware](https://github.com/JF002/InfiniTime), chosen as it provides basic watch functionality. This smartwatch has qualities found normally in mainstream fitness trackers:

* Touchscreen
* 3-axis accelerometer (capable of a signal response up to 200Hz)
* Bluetooth BLE 4.0 communication
* Controllable vibration motor to provide haptic feedback
* 70mAh Battery
* Heart-rate monitor

It is the onboard software (i.e. firmware) that sets Cue Band apart from consumer devices. Our custom firmware allows the device to be updated or reprogrammed over-the-air via a Bluetooth device such as a smartphone. This means that it is possible to change and update the functionality of any Cue Band device remotely via the user's smartphone. There are no restrictions on the amount of times that the device can be updated or reprogrammed, making this an exciting device for future healthcare interventions.

Currently we are exploring the application of Cue Band to deliver haptic cueing for people with Parkinson's experiencing drooling.  While existing fitness trackers are able to vibrate and provide notifications, they are limited in the control over the vibration motor and those actions are typically driven by the smartphone – i.e. rely on the connection with the smartphone to instruct the fitness tracker to take action. Whereas Cue Band has been designed as a standalone solution, meaning that once the device has been programmed with the 7-day cueing schedule, it is possible to then disconnect the smartphone (or leave it at home) and still receive the cueing prompts. 

All our software are open-source technologies and available for anyone to inspect, use or repurpose. Many commercially available wearable devices are closed source or ’black-box’ technologies that obfuscate the firmware and algorithms to perform physical activity and sleep monitoring. As such, it is difficult to assess how appropriate those algorithms are for people with Parkinson's therefore how accurate the reported data are. The open source design of Cue Band means that any publications or anonymous datasets resulting from the device can be scrutinised and validated against other open source datasets and algorithms.

<h3 id="about-mobile-app"> The Mobile Application - Cue Band App </h3>

The Cue Band App is a mobile application that serves as a companion to the Cue Band wearable. Through it, the user will be able to create a 7-day schedule of cueing time, start and stop cueing at any moment, define the intensity, type (mobile vibration, audio or band vibration) and where to receive the cueing, and create daily self-reports to register drooling symptoms.

The app uses the smartphone's Bluetooth to communicate with Cue Band, allowing the schedule to be set in the smartwatch and, at the same time, collect data of the smartwatch daily usage. Through Bluetooth, the app will also be able to install new versions on the smartwatch firmware.

This app will be available on both iOS and Android. Since we aim to make it available to the most smartphones possible, we are targetting the minimal required version to Android 5.0 and iOS 9.


<h3 id="about-data"> Data collected </h3>

The type of data collected from participants depends on what particiapants allows us to. We will never collected data from particiapnts without their permission, allowing this way users to decide want they want to share with us.

All collected data will be safely stored in a database, only directly accessible by the researchers involved in this study. If you wish to get all the data we collect from you, you can either contact us or directly download it through the app. 

From the mobile application and wristband, we will collect two types of data:

1) Anonymous data analysed at an aggregated level - This includes data like wear time of the wearable, activity data and sleep behaviours. This type of data is opted‐in, as the participant can choose if they want to share it or not.

2) Identifiable data - This includes cueing schedules created by the participants, feedback given through the app, self‐report diaries with drooling scales, age range, ethnicity and address.




<h2 id="about-studies">  Studies </h2>
![image info](/images/study.png)

Our study explores the potential effects of different cueing methods on the perceived drooling severity and frequency. We will conduct a comparison study between receiving prompts for swallowing from the smartphone app and the wristband wearable. Participants will experience both cueing methods at determined intervals of 3 weeks and register daily their symptoms and experiences throughout the study.

We aim to recruit a total of 3000 people with Parkinson’s, which will receive a wristband to use in their daily life as they wish, contributing to the study through anonymous usage data. From these 3000 participants, we will recruit 300 for the formal comparison study between cueing methods over eight weeks. Every participant can keep the wristband for their daily life after the study ends if they wish to do so.

<h3 id="about-formal-study"> Formal Study </h3>
We will recruit 300 people with Parkinson’s (10% of the total number of participants) to participate in our eight-week cueing intervention study. In this study, participants will be divided into two groups (Group A & B). Each participant will experience both interventions (wristband wearable and smartphone app only) in separate periods. They will be asked to use an intervention for three weeks.  After three weeks, participants will receive the alternative intervention for another three weeks. During this time, participants will be asked to maintain a daily diary using the tools provided through our mobile app. They will self-report on their swallowing severity, frequency, and duration and provide any additional comments or reflections on their experiences that day. Before and after each intervention method, participants will also complete formal assessments of their symptoms.

Before receiving the interventions, participants will complete a two-week baseline during our onboarding phase. During which they complete the daily diary (drooling severity chart) and self-reporting without any intervention.

A subgroup who express an interest, will enter a 3 week phase at the end of the interventions, when they receive neither intervention to see if there is a carry over effect.  They will then have the same follow-up assessments as at the end of the intervention period prior to exiting the study.  

Following the intervention phase of our study, participants will be asked to complete a questionnaire about their experience and preferences regarding both the wristband wearable and smartphone app.

<h3 id="about-free-living-study"> Free-Living Study </h3>
We will recruit 2700 people with Parkinson's (90% of the total number of participants) to use the wearable and the app freely in their daily lives. They will only be providing anonymous usage data (i.e. cueing schedule, physical activity and sleep behaviours). At the same time, they also can give feedback and suggestions through the mobile app.

<h3 id="about-timeline"> Timeline </h3>
{% include timeline.html %}


