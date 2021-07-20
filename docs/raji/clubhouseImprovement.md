---
layout: default
title: Things for Improvement in Clubhouse
parent: Raji
grand_parent: Projects
nav_order: 3
permalink: /projects/raji/clubhouseImprovement
---

# Things for Improvement in Clubhouse

While implementing Raji, I also find some points that could be improved in Clubhouse.

## No Horizontal Scrollbar in Milestones Page

When there are too many milestones, there's no horizontal scrollbar on the Milestones page. Users could only see the last milestones by filtering the results.

![Milestone improvement](https://raw.githubusercontent.com/cwang1221/cwang1221.github.io/main/images/milestoneImprovement.png)

## Epic State Inconsistent
On the Epics page, there are inconsistent terms (To Do, In Progress, Done v.s. Unstarted, Started, Done) for epic states. Which may confuse the user.

![Epic state inconsistent](https://raw.githubusercontent.com/cwang1221/cwang1221.github.io/main/images/epicImprovement.png)

## Different Floorplan on Stories Page
On the Stories page, the filter bar is shown as a left sidebar. While other pages are showing the filter bar on the top. It's better to make them consistent.

![Differen floorplan](https://raw.githubusercontent.com/cwang1221/cwang1221.github.io/main/images/storyFilter.png)

## Inconsistent Terms in Story Filters
The **Workflow State** filter on the Stories page is using singular while others are plural.

![Inconsistent terms](https://raw.githubusercontent.com/cwang1221/cwang1221.github.io/main/images/storyFilterPlural.png)

## The Behavior of Progress Bar in Epics Page is Incorrect
When there's no "Not Started" story in an epic, the progress bar's behavior is incorrect. Take the following screenshot as an example, there's one "Completed" story and one "In Progress" story. Both of them should take 50% of the full width.

![Incorrect Progress Bar](https://raw.githubusercontent.com/cwang1221/cwang1221.github.io/main/images/epicProgressBar.png)