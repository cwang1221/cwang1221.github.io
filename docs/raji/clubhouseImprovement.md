---
title: Things for Improvement in Clubhouse
parent: Raji
has_children: false
nav_order: 3
---

# Things for Improvement in Clubhouse

While implementing Raji, I also find some points that could be improved in Clubhouse.

## No Horizontal Scrollbar in Milestones Page

When there are too many milestones, there's no horizontal scollbar on the Milestones page. User could only see the last milestones by filtering the results.

![Milestone improvement](https://raw.githubusercontent.com/cwang1221/cwang1221.github.io/main/images/milestoneImprovement.png)

## No Busy Indicator after Creation

After creating a new object (e.g. story), there's no busy indicator on the page. User can only wait for a while to see the newly created object.

There could be two better approaches:
1. Showing a busy indicator after clicking the create button.
2. Optimistic creation. When user clicks the create button, we will optimistically consider the request as success and render the newly created item immediately. If the request failed, we will then show an error message and remove the object from UI.

## Epic State Inconsistent
On the Epics page, there are inconsistent terms (To Do, In Progress, Done v.s. Unstarted, Started, Done) for epic states. Which may confuse the user.

![Epic state inconsistent](https://raw.githubusercontent.com/cwang1221/cwang1221.github.io/main/images/epicImprovement.png)

## Different Floorplan on Stories Page
On Stories page, the filterbar is shown as a left side bar. While other pages are showing the filter bar on the top. It's better to make them consistent.

![Differen floorplan](https://raw.githubusercontent.com/cwang1221/cwang1221.github.io/main/images/storyFilter.png)

## Inconsistent Terms in Story Filters
The **Workflow State** filter in Stories page is using sigular while others are plural.

![Inconsistent terms](https://raw.githubusercontent.com/cwang1221/cwang1221.github.io/main/images/storyFilterPlural.png)

## Behavior of Progress Bar in Epics Page is Incorrect
When there's no "Not Started" story in an epic, the progress bar's behavior is incorrect. Take following screenshot as an example, there's one "Completed" story and one "In Progress" story. Both of them should take 50% of the full width.

![Incorrect Progress Bar](https://raw.githubusercontent.com/cwang1221/cwang1221.github.io/main/images/epicProgressBar.png)