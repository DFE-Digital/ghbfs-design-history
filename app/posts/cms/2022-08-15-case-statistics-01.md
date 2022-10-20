---
title: Operational overview of cases - Case statistics
description: A complete redesign of the case statistics page within the CMS
date: 2022-08-15
screenshots:
  items:
    - text: Case statistics
      src: case-statistics-v1.png
    - text: Case statistics drilldown
      src: case-statistics-drilldown-v1.png
    
---

## What we changed
- We removed all the original design and started from scratch expept the 'download csv' button as we knew that was still being used.
- We added in just operational data such as cases with the status of open, on-hold or new.
- We added the ability to drilldown into tower level cases.
- We added more detail relevant to the towers.
- More visibility on how many cases are missing a stage or level data.

## Why we changed this
We know that the previous version of the case statistics was not being used as it was structured into sub category and not set up to work the way proc ops do in their towers.
We know that more historical data is held in PowerBi but there was still a need to see what was happening with cases right now.
We know that proc ops use trackers alongside the CMS and they report on number of cases within a tower at different stages.

## How it works
We have kept the 'case statistics' menu item in the top navigation.
The first page contains an overview all the live cases across all the towers. We then start to break down in open, new and on-hold and there is further breakdown into towers where we start to add more granualar detail.
For each tower we have made it possible to click through to view all live cases within that tower but with much more information.

## Further considerations
After reviewing we know that we need to consider the value of cases, this is important to proc ops and the project.
We can do more to help with missing data and getting to view cases within a specific tower or status.