# Project Snapshot: UI and Remote Operation S26

- Owner: `JACart2`
- Project: `14`
- Project URL: https://github.com/orgs/JACart2/projects/14
- Generated: `2026-02-23 15:39`
- Filter: **All Columns**
- Items: **14**

---
# Sprint Planning Overview

<!--- (Provide a high-level overview of your sprint goals.) --->

We are focusing on doucmenting existing code in both the UI and Dashboard repositories under the HCI umbrella. At the same time, we will be integrating voice communication and commands with the Madison JACart. By the end of this upcoming sprint, we want to have Madison listening for voice commands as well as a deep understanding of our codebases through documentation.

# Issues

## Column: Semester Todo

### Issue JACart2/dashboard#14: Verify that the server that communicates with the dashboard is accessible and working

- Link: https://github.com/JACart2/dashboard/issues/14
- **Open** • Author: @lukeb-cs • Created: `2026-02-06T02:07:24Z` • Updated: `2026-02-06T02:07:24Z`

#### Description

## Summary

Verifying that the server used in previous semesters is accessible to our team and fits the demands of our project intentions

---
## Motivation

To allow to dashboard to interface correctly with both JACarts

---
## Success Metrics (REQUIRED)

Information will be published to the dashboard by each cart including requests for help, position, current target location, etc.

## Demo Plan (REQUIRED)

Record different status messages on the dashboard as well as other information like position and target location

---

---
### Issue JACart2/dashboard#15: Verify that the cart can request for help

- Link: https://github.com/JACart2/dashboard/issues/15
- **Open** • Author: @CalebM-2 • Created: `2026-02-09T20:17:54Z` • Updated: `2026-02-09T20:17:54Z`

#### Description

## Summary
Ensure that the carts can notify admin about the state of the cart, meaning the cart and admin are communicating over a working server.
---
## Motivation
The cart communicating with the admin is a large safety feature. If problems arise with the cart OR passenger in route is in route to its destination, the admin NEED to be notified about the situation.
---
## Success Metrics (REQUIRED)
This will be a success if when the passenger is on the golf cart, and presses the "get help" button, that the central admin computer receives a notification detailing the carts status in terms of speed, location and orientation. Not only will they receive cart data, but also passenger data with the passengers movement in mind using the camera.
---
## Demo Plan (REQUIRED)
With an operating golf cart headed to a destination, we will have a passenger press the request help button. From there we will check the admin laptop to check the notification, ensuring that the cart data as implied earlier has been sent to the admin. There will also be pictures or video of the passenger in case if an emergency to the passenger.
---
## Risks / Dependencies
There is currently no risk to break existing cart to admin communication as it is not functional.

---
### Issue JACart2/dashboard#18: Ensure admins can see real time status of cart during operations

- Link: https://github.com/JACart2/dashboard/issues/18
- **Open** • Author: @daffyfn902 • Created: `2026-02-10T00:11:17Z` • Updated: `2026-02-12T17:45:28Z`

#### Description

## Summary
Add additional cart states so that admins can always monitor the real time status of each cart.

---
## Motivation
Admins can quickly identify and respond to issues, reducing downtime and improving user satisfaction.

---
## Success Metrics
Both carts display a clear, up to date status in admin backend interface, reduction in time for admins to detect issues.

---
## Demo Plan 
Simulate different instances of cart statues and confirm that admin dashboard recognizes and reports these statuses.

---
### Issue JACart2/dashboard#19: Ensure dashboard displays "No connection" when cart is not in use

- Link: https://github.com/JACart2/dashboard/issues/19
- **Open** • Author: @daffyfn902 • Created: `2026-02-10T00:23:03Z` • Updated: `2026-02-10T00:23:03Z`

#### Description

## Summary
Confirm that dashboard displays "No connection" when the cart is disconnected
---
## Motivation
Showing a definitive No connection state for inactive carts can reduce confusion and ensure accurate monitoring

---
## Success Metrics
All inactive carts display No connection status in dashboard

---
## Demo Plan 
Simulate both carts in both online and offline statuses and confirm that message is correctly displaying the statuses

---
### Issue JACart2/dashboard#20: Add video recording or picture ability from cart to dashboard for help requests

- Link: https://github.com/JACart2/dashboard/issues/20
- **Open** • Author: @daffyfn902 • Created: `2026-02-10T00:27:43Z` • Updated: `2026-02-10T00:27:43Z`

#### Description

## Summary
Give dashboard operator the ability to see a video recording or pictures from the cart at the time of help request
---
## Motivation
Provides visual context to help requests allowing operators to asses situations quickly and provide accurate support

---
## Success Metrics
Operators can access video or photo recordings from the cart for all help requests

---
## Demo Plan 
Trigger a test help request and confirm that operator dashboard displays associated content

---
### Issue JACart2/dashboard#21: Final documentation for new code

- Link: https://github.com/JACart2/dashboard/issues/21
- **Open** • Author: @daffyfn902 • Created: `2026-02-10T00:34:35Z` • Updated: `2026-02-10T00:34:35Z`

#### Description

## Summary
Finalize documentation for all new code
---
## Motivation
Ensures readability and comprehension for new and future developers

---
## Success Metrics
Properly showcase data flow between files and repos, all new functions classes and modules with descriptive comments

---
## Demo Plan 
Select a few files and ensure proper documentation for all functionality in files

---
### Issue JACart2/ui#67: Make sure that paths are visualized on the dashboard as well as the user interface

- Link: https://github.com/JACart2/ui/issues/67
- **Open** • Author: @lukeb-cs • Created: `2026-02-06T02:11:44Z` • Updated: `2026-02-06T02:11:44Z`

#### Description

## Summary

Verify that the existing UI functions as intended, displaying critical cart information in real time along with attempting to publish information to the dashboard server

---
## Motivation

Basic functionality of the cart relies on the function of the UI and Dashboard systems

---
## Success Metrics (REQUIRED)

Cart paths are displayed in real time on the screen in front of the user along with other helpful information about the course the cart is taking

---
## Demo Plan (REQUIRED)

Cart UI functions as intended by previous semesters. Paths and destinations are shown to the user appropriately alongside other useful information

---

---
### Issue JACart2/ui#68: Screen displays "stopping"

- Link: https://github.com/JACart2/ui/issues/68
- **Open** • Author: @CalebM-2 • Created: `2026-02-09T20:59:00Z` • Updated: `2026-02-09T20:59:00Z`

#### Description

## Summary
Screen displays "stopping or stopped" when user presses stop button on UI.
---
## Motivation
With a stop button on a screen, you do not want to accidentally press the button without knowing and questioning why the golf cart it stopping. With this added feature, there will be no question as to why the golf cart is stopping. 
---
## Success Metrics (REQUIRED)
This will be a success if when the golf cart is driving to a destination and the stop button is pressed, the UI will display the word "stopping" to notify the passenger that the stop button was pressed. The word "stopped" will then be displayed when the cart reaches a speed of 0, disappearing after a few seconds.
---
## Demo Plan (REQUIRED)
The golf cart will be enroute to a desired location, when the passenger will press the stop button. The UI should then display the word Stopping to notify the user that the stop button was pressed and it is working. The word stopped will appear when the cart is completely stopped, disappearing momentarily. 
---
## Risks / Dependencies
There is a risk of damaging the current UI when attempting to add this new feature. It will require us to be careful when working around the existing UI code.

---
## Column: Sprint Todo

### Issue JACart2/dashboard#16: Get Madison responding to keyword Madison

- Link: https://github.com/JACart2/dashboard/issues/16
- **Open** • Author: @CalebM-2 • Assignees: @CalebM-2, @daffyfn902, @lukeb-cs • Created: `2026-02-09T20:30:49Z` • Updated: `2026-02-23T20:24:25Z`

#### Description

## Summary
The cart Madison will react to voice command Madison.
---
## Motivation
Both carts should have voice commands working, which starts with keyword madison.
---
## Success Metrics (REQUIRED)
How will we objectively verify this is complete?
Be specific:
When the cart UI is launched, and the microphone has been given permission to use audio, Madison will simply require the keyword Madison to then listen for keywords. This test will be successful if Madison then is in a state to accept the next command.
---
## Demo Plan (REQUIRED)
With the golf cart outside yet to move, the passenger will activate Madison's voice commands by saying the word "Madison". From there the golf cart will be ready to accept the next command, which will be made clear by the program printing awaiting next command in the terminal.
---
## Risks / Dependencies
Madison currently does not have functional voice commands working, so there should be low to no risk.

---
### Issue JACart2/dashboard#17: Get Madison responding voice controls

- Link: https://github.com/JACart2/dashboard/issues/17
- **Open** • Author: @CalebM-2 • Assignees: @CalebM-2, @daffyfn902, @lukeb-cs • Created: `2026-02-09T20:40:10Z` • Updated: `2026-02-23T20:24:41Z`

#### Description

## Summary
The cart Madison will react to voice controls allowing for passenger to be able to speak their preferred destination.
---
## Motivation
This will lessen the discrepancy between the two carts, so that when future testing occurs, both James and Madison are applicable to the tests.
---
## Success Metrics (REQUIRED)
How will we objectively verify this is complete?
Be specific:
When the cart UI is launched, and the microphone has been given permission to use audio, Madison will simply require the keyword Madison to then listen for keywords. This test will be successful if Madison follows the (known) commands given.
---
## Demo Plan (REQUIRED)
With the golf cart outside yet to move, the passenger will activate Madison's voice commands by saying the word "Madison". From there the passenger can give commands to a destination, with the golf cart then going to the desired destination
---
## Risks / Dependencies
Madison currently does not have functional voice commands working, so there should be low to no risk.

---
## Column: In Progress

### Issue JACart2/dashboard#13: Write documentation for the Dashboard repo

- Link: https://github.com/JACart2/dashboard/issues/13
- **Open** • Author: @lukeb-cs • Assignees: @CalebM-2, @daffyfn902, @lukeb-cs • Created: `2026-02-06T02:01:01Z` • Updated: `2026-02-23T20:23:16Z`

#### Description

## Summary

Add comments to all files in the Dashboard repo to fully document code processes

---
## Motivation

To help future research students understand code and to learn more about the codebase ourselves

---
## Success Metrics (REQUIRED)

Checking for comments in the files inside the Dashboard repository

---
## Demo Plan (REQUIRED)

Comments will be visible at different points throughout the codebase

---

---
### Issue JACart2/ui#66: Write documentation for the UI repo

- Link: https://github.com/JACart2/ui/issues/66
- **Open** • Author: @lukeb-cs • Assignees: @CalebM-2, @daffyfn902, @lukeb-cs • Created: `2026-02-06T02:00:20Z` • Updated: `2026-02-23T20:22:44Z`

#### Description

## Summary

Add comments to all files in the UI repo to fully document code processes

---
## Motivation

To help future research students understand code and to learn more about the codebase ourselves

---
## Success Metrics (REQUIRED)

Checking for comments in the files inside the UI repository

---
## Demo Plan (REQUIRED)

Comments will be visible at different points throughout the codebase

---

---
## Column: Done

### Issue JACart2/av_course_spring26#10: Add node for Luke Brenningmeyer to the JACart Warmup Project

- Link: https://github.com/JACart2/av_course_spring26/issues/10
- **Closed** • Author: @lukeb-cs • Created: `2026-01-29T18:51:15Z` • Updated: `2026-02-22T21:49:41Z`

#### Description

_(No issue/PR description/body provided.)_

---
### Issue JACart2/dashboard#12: Create Diagram to Document Existing Codebase

- Link: https://github.com/JACart2/dashboard/issues/12
- **Closed** • Author: @lukeb-cs • Assignees: @CalebM-2, @daffyfn902, @lukeb-cs • Created: `2026-02-05T18:12:57Z` • Updated: `2026-02-23T20:14:58Z`

#### Description

## Summary

Design a diagram that encapsulates all relevant files to the current program in order to better document code

---

## Motivation

This is necessary in order to help future research groups to better understand the actions taking place inside of the existing codebase.

---

## Success Metrics (REQUIRED)

When a file has been produced which encapsulates all relevant program files and their actions in relation to one another, we will have succeeded in this action.

## Demo Plan (REQUIRED)

The file will be available in the repository to document the codebase.

---

## Risks / Dependencies

N/A

---
