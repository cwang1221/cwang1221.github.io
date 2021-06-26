---
title: Meeting Timer
parent: Raji
has_children: false
nav_order: 2
---

# Meeting Timer

Meeting timer is a functionality, that no other Jira-like product has. The idea comes from my daily work.

![Meeting Timer](https://raw.githubusercontent.com/cwang1221/cwang1221.github.io/main/images/meetingTimer.png)

Everyday our team has a daily meeting, in which we will check the Jira boards and everybody summarizes what he / she has done yesterday and which problem he / she has met.

Normally the meeting should be short, if there's any complex issue we shall discuss it later in another meeting. But sometimes a colleague may talk too much about the details and it takes too much time of others.

So I developed a Chrome extension called [Scrum Timer](https://chrome.google.com/webstore/detail/scrum-timer/nnbobiopmflhekiicebfiohdfbdgbgbi), which could help the scrum master to control the meeting time. I also included this functionality into Raji.

## How to Use

### Set Time per Topic
Firstly you need to set how much discussion time a topic could take.
1. Click avatar in the bottom left corner.
2. Click **Setting**.
3. Set the time (in seconds) in **Time per Topic**. The valid range is 1~300.
4. Click **Save** to save your change.

![Set time](https://raw.githubusercontent.com/cwang1221/cwang1221.github.io/main/images/setTime.gif)

### Start Meeting
After setting the time, you could start using the functionality in any page.
1. Click on the **Start Meeting** button on the upper right corner, it will start the timer.
2. When the discussion of a topic is finished, you could switch to the next topic by clicking the **Next Topic** button. You could also end the meeting by clicking the **Stop Meeting** button.

![Meeting](https://raw.githubusercontent.com/cwang1221/cwang1221.github.io/main/images/startMeeting.gif)

When the discussion exceeds the time, the header will blink to remind the team: This topic is too complex to discuss now, let's go for the next one!

![Time up](https://raw.githubusercontent.com/cwang1221/cwang1221.github.io/main/images/timeUp.gif)
