---
published: true
layout: post
category: guidelines
tags:
 - data-experience
 - powerbi
title: Eight Essential Steps for Building Great Data Experiences
---

Do you want to create great data experiences? Follow these eight essentials (guidelines) and elevate your regular reports into great data experiences. A great data experience should have these goals at top-of-mind: 

* the clear interpretation of transferred information
* the origin of the question (why are users asking this question)
* the possibility to answer the next question
* the motivation for these data-driven decision
* the connection to business processes

## Essential \#1: think about your end-users' needs

Don't just focus on building your report, but focus on the report's audience you're building the indented report for. Don't do this in isolation. Get your end-users involved in the process and get your end-users to think of this process in more of an iterative way. Try to get early feedback as soon as possible to minimize wasted effort. It is also good for you to continue your end-user feedback loop because user requirements are dynamic and will change over time. 

![iterative approach](/assets/posts/2021-04-31-eight-essential-steps-for-building-great-data-experiences/orig1x800.png)

## Essential \#2: design the layout with the user in mind

Once you have a good understanding of the questions your end-users care about, it is important that your report and page layout are designed with the end-user in mind. The first recommendation or guideline is to identify the subject or topic of the report page.

![report layout](/assets/posts/2021-04-31-eight-essential-steps-for-building-great-data-experiences/orig2x800.png)

The intent is that a user can quick glance over your report and pages and quickly understand what types of questions this report can answer. Chose simplicity and avoid clutter. Generally, you will want to have a consistent layout to help drive a good user experience positioning the most important visuals from upper left to bottom right. If you're going to use slicers, try to keep the slicers in the same spot for end-users.

## Essential \#3: use the right charts for the right purpose

In building a great data experience it is important you are using the right charts for the right purpose. Now, Power BI has a ton of visuals to choose from including built-in and Microsoft's whole [marketplace](https://appsource.microsoft.com/en-us/marketplace/apps?product=power-bi-visuals) eco-system. While this cheat sheet does not include all the possible visuals, it does show some of the most common visuals and there common use cases.

![charts and use cases](/assets/posts/2021-04-31-eight-essential-steps-for-building-great-data-experiences/orig3x800.png) [bigger](/assets/posts/2021-04-31-eight-essential-steps-for-building-great-data-experiences/orig3.png)

## Essential \#4: allow interactivity and exploration

In building a great data experience, the last thing you want are end users feeling like they are hitting a dead end. That is why the next essential is allowing end users to explore and interact with data and report. This can include supporting natural queries with Q&A visual to adding drill through / drill down functionality in your report. This elevates your report by empowering users to explore the data and answer their own questions. 

## Essential \#5: help users go from insights to action

In the previous essentials, we talked about it making easier for users to read and interpret the data correctly along with making it easier for users to explore the data. This essential is about making it easier for users to act on those insights. The most valuable insights are the ones that spark action. So make it easy for your end users to find these insights __AND__ make it easy for them to act on those insights. This may be accomplished by allowing end users to trigger automation right from the report. Power BI is a little bit behind in this area but the Power BI Product Team really listens to the Power BI Community. Recently they introduced a visual that will allow integration to [Power Automate](https://powerbi.microsoft.com/en-us/blog/announcing-the-new-power-automate-visual-for-power-bi-reports/) and [Power Apps](https://powerbi.microsoft.com/en-us/blog/from-insights-to-action-with-the-power-apps-custom-visual/).

## Essential \#6: make your reports accessible

Everyone reads, understands and interfaces with data differently. Keep in mind that users have individuals preferences and constraints and that data experience you build is a form of communication. Consider users that have the following:

* User with low vision, colorblind, or are blind
* Users with motor disabilities
* Users with dyslexia and other cognitive impairments

One way to help everyone is to improve the ease-of-consumption.

* Reduce how much your audience will have to infer or approximate
* Include relevant contextual or technical information
* Avoid redundancy and unnecessary elements
* Maintain consistent font and style

Making your report accessible may include:

* Configuring your report to be interfaced with in multiple ways \(alternative test, tab order, visual sort order\)
* Label and differentiate data in accessible ways \(color contrast, friendly color palette, data labels, markers, images and tooltips\)

## Essential \#7: invest in on-the-go data experiences

Invest in on-the-go data experiences especially now when people are moving a lot of their business work onto their phones. Make sure that our report is accessible from mobile devices. Take advantage of the Mobile Layout Feature and design for vertical/scrolling layout with a touch interface.

## Essential \#8: invest in performance optimizations

The last essential is a very broad topic but something very important to the quality of interactivity to your reports. This is performance. Slowness is normally the result in a large amount of data and/or the number queries your report requires to run. When you look at performance as a function of volume try to:

* Reduce the amount of data \(or take advantage of aggregation features\)
* Reduce the number of visuals on a single page
* Reduce interaction between visuals
* Look at DAX vs Model vs PowerQuery vs Source System and are you placing your business logic in the correct spot. 

## Keep the objective in mind

So just don't build a report, build a great data experience! As a general recap, keep this in mind.

* Understand your end-user
* Use the report layout to give structure to the story
* Use the right charts for the right purpose
* Send your users on an adventure through interactivity and exploration experiences
* Make the data experience easy to access, use and act on. 
