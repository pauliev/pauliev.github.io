---
published: true
layout: post
category: guidelines
tags:
 - dataflows
 - powerbi
title: Four Great Reasons to use Power BI Dataflows
---

Four great reasons for using Power BI Dataflows!

## 1\. Reuse Transformation Logic

You can use dataflows to create reusable transformation logic that can be shared by many datasets. Dataflows promote reusability and prevents the need to create separate connections to data sources.

## 2\. Get Your Data Outside of Power BI

You can use dataflows to expose the data in your own Azure Data Lake Gen 2 storage (ADLSv2), enabling you to connect other services to the raw underlying data.

## 3\. Single Source of Truth

You can use dataflows to create a single source of the truth by forcing analysts to connect to the dataflows, rather than connecting to the underlying systems, providing you with control over which data is accessed, and how data is exposed to report creators.

## 4\. Reduce Load on Systems

With dataflows you can prevent analysts from having direct access to the underlying data source. Since report creators can build on top of dataflows, it may be more convenient for you to allow access to underlying data sources only to a few individuals, and then provide access to the dataflows for analysts to build on top of. This approach reduces the load to the underlying systems, and gives administrators finer control of when the systems get loaded from refreshes.
