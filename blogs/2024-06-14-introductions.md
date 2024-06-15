---
layout: post
title: Introudcting AINA ⠕ SCAN
tags: startup
published: true
date: 2024-06-14
author: Devin Dennis and Jack Mead
---
# AINA⠕SCAN

We are a small team of software engineers and coffee enthusiasts who are passionate about agricultural technology and are hoping to make a positive impact on the coffee farming community through our innovative computer vision software and data platform built with and for coffee farmers. We are building up a dataset with the support of the Kona coffee community in order to produce advanced machine vision models which power our easy to use mobile and web applications.

![alteri](/images/2024-06-14-introductions/alteri.jpg "Farm in Boquete, Panama") ![team](/images/2024-06-14-introductions/team.jpg "Team in Boquete, Panama") ![kmt](/images/2024-06-14-introductions/kmt.jpg "Farm in Kona, Hawai'i") 

<!-- <div style="overflow: hidden; display: flex; justify-content: center; align-items: center;">
    <img src="/images/2024-06-14-introductions/team.jpg" title="Team members in Boquete, Panama". alt="team" style="border-radius: 20px">
</div> -->

## Platform

The Ainascan platform is purpose built to help coffee farmers learn more about their crops and give them a chance to optimize their spending on pesticides, herbicides, and fertilizer. Our platform features many layers of artificial intelligence that:

- Identify individual berries on a coffee tree and produce an estimated count of the total number of berries and further classify them by their lifecycle.

- Identify individual leaves on a coffee tree and produce an estimated count of the total number of leaves and further classify them by their health.

- Predict specific diseases, deficiencies, and pests that are present on the coffee tree leaves.

With these powerful predictions, our platform will provide farmers with detailed insights into their crops. They can know the ratio of ripe to unripe berries (even predicting it into the future) to determine when to harvest. Knowing when to harvest is important to each individual farmer as it has large impacts on the prices of their yield, quality, and flavor. Farmers will know what diseases are present to determine if a treatment plan is needed and if there are deficiencies in an area to determine if a fertilizer is needed. Instead of indiscriminately spraying an entire field on a regular schedule, our platform will suggest that only a given area needs to be treated in order to reduce the supply needed. Our models seek to provide all these insights with educational resources and detailed suggestions on how to handle the given issue.

With the introduction of this blog, the Ainascan application is officially under development. The team is currently developing our mobile application: HuaScan and our web application: Makapp. The mobile application is our data collection tool. It will allow coffee farmers to take individual pictures of their crops to get instant reports on the density and presence of any leaves, berries, and diseases detected. To support our web application, the “field survey” feature will allow a user to walk through their farm or sections of their farm and collect a dataset which can be uploaded when they have connectivity. The results of the field survey would be processed and presented in Makapp. 

The web application, Makapp, will provide a unified interface where coffee farmers can review and analyze the results of all the data they have collected and processed. The interface would display a variety of heatmaps and distribution statistics, allow the user to review collected images, review suggested treatment plans, and provide estimations on cost savings and yield numbers. This web application will also serve as a form of bookkeeping so that farmers can track what herbicide and pesticide treatments they applied to various sections of their farm and monitor the effectiveness of their treatment plans.

## Vision

Our vision for the technology is founded on four principals:

### Innovation

We utilize state of the art artificial intelligence trained on expertly annotated datasets from all over the world to deliver the most accurate data possible. We utilize the most advanced computer vision and LLM technologies to analyze coffee crops so results come fast, clean, and accurate.

Our platform is built on top of open-sourced technologies and frameworks so we can reduce costs while maintaining a stable and flexible environment. This allows us to rapidly innovate and create new features quickly while supporting existing ones.

Our user facing applications are built with modular design first. Coffee is just one critical agricultural crop we are studying. But our user interface allows farmers to overlay data about many different crops, weather patterns, and more. As more research is done on different crops, these features will be integrated seamlessly into the application.

Our data platform is also built with modular design as well. As datalakes become large, they are difficult to maintain and annotate. We have built ours to quickly ingest datasets that are immediately available to the user facing applications while maintaining a library that allows us to know what data we have.

### Education

Our suite of technologies is made to educate farmers on their crops in a very easy to understand fashion. We have found that many small-time farmers don’t know enough about their crops and are subject to the guidance of big agricultural companies that try to up-sell and over-sell products to them. We strive to create a community of knowledgeable farmers and scientists to give us the most up-to-date academic research and practices that know what works and what doesn’t.

### Cost Effective

Many small time farmers cannot use technology in their operations as what is available to them is far too costly. Our platform is meant to run as efficiently as possible using open sourced standards that can run on a computer at home or in the cloud. Having this flexibility in our platform makes it cheap for farmers to use and puts them in charge of their data.

### People Focused

We are building a people-first application. This means we are building exactly what our customers want to see and what makes intuitive sense to them. Yes, our platform will allow you to see the nitty gritty details on how the AI is operating. But it will also give you exactly the information you need: how much is this going to save me? How much time am I going to spend? Where do I need to go? What do I need to buy?

## Challenges

The Ainascan platform has a lofty vision which can not be accomplished easily and requires a lot of input and feedback from the community. The team has visited numerous Kona coffee farms on Hawai’i island and in Boquete, a region in Chiriqui, Panama. This experience has opened our eyes to the complexities that small and medium coffee farmers face on a daily basis. The platform we are aiming to build must be inclusive and representative of coffee practices and operations that span a global user base. For it to be useful to farmers and researchers alike, it must be primarily influenced and owned by the coffee farming community.

### Product Development Challenges

The Ainascan platform faces two primary product development challenges - the mobile application, HuaScan, and the web application, Makapp.

The mobile application, HuaScan, will need to be developed in a way that provides a clean and concise UI/UX so that farmers can easily collect data and understand any insights they receive back. The mobile application should also support offline use cases as many farms are located in remote regions of the world where connectivity is not available. A user should be able to walk around their farm and collect a dataset that can be uploaded in the background once they are connected to wifi or have cellular service. This application should work seamlessly in order to keep the user's interest. Users are using their valuable time to collect data on this application so retention and reliability are utmost concerns.

The web application, Makapp, could suffer from over-engineering if the team does not clearly identify specific requirements. This application could become very large, so we are challenged to become proactive in our communication and understand at a modular level what needs to be accomplished. The project development for Makapp will evolve overtime as we learn more from stakeholders and build out HuaScan for data collection.

### Engineering Challenges

The Ainascan platform is built off insights from a computer vision model which needs to be trained on a large dataset. Assuming a large dataset could be collected and trained, the reality of having coffee farmers capture routine datasets for analysis in the platform poses a great challenge. Capturing the entirety of a single coffee tree in a single photo would require a very high resolution camera taken in very optimal lighting conditions. Additionally, capturing large datasets from a coffee farm that spans many acres of land on a routine basis requires a lot of manual effort. In an ideal world, we could capture a datapoint from each tree on a coffee farm on a routine basis. However, this is just not realistic given the operational overhead. WIth only a smartphone, large scale data collection will always be challenging. In the future, we will experiment with robotics like drones to help in the collection of data.

The team currently consists of two software engineers completely self-funded so any work we accomplish on the project should be cost effective. We are developing the platform on our own servers that we host in our homes so we are limited by some degree to our compute and storage abilities. In order to run this entirely by ourselves, the platform is built off open source / cloud native technologies like Kubernetes. This introduces a degree of complexity to the architecture as the platform from bottom to top will be managed and hosted by us.

## Looking Ahead

This is just the start. As we begin development, we have big dreams of helping farmers from all over the world. To start, we have a working goal of getting an alpha release of HuaScan within the next 2-3 months. If you are a coffee farmer interested in using the product, a scientist interested in the datasets we have already captured, an engineer interested in contributing to the software, or simply want to support our community and initiative, consider joining our community!
