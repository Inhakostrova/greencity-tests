Test Case ID

TC-01

Title:

Join event successfully

Date Created:

30-03-2026

Author:

Inha Kostrova

Priority: Medium

Preconditions:

1.User is registered

2.User is logged in

| Step | Action | Data | Expected Result |
| :---- | :---- | :---- | :---- |
| 1 | Click “Join event” button | \- | Button is clickable |
| 2 | Confirm action (if applicable) | \- | User is added to the event |
| 3 | Check button state | \- | Button changes state “Joined” |

Test Case ID

TC-02

Title:

Add event to favorites

Date Created:

30-03-2026

Author:

Inha Kostrova

Priority: Medium

Preconditions:

1.User is registered

2.User is logged in

 

| Step | Action | Data | Expected Result |
| :---- | :---- | :---- | :---- |
| 1 | Click “bookmark” iron | \- | Icon changes state |
| 2 | Check event | \- | Event is added to favorites |
| 3 | Refresh page | \- | Event remains in favorites |

Test Case ID

TC-03

Title:

Event card displays correct information

Date Created:

30-03-2026

Author:

Inha Kostrova

Priority: Medium

Preconditions:

1.User is registered

2.User is logged in

3.Events are available on the page

| Step | Action | Data | Expected Result |
| :---- | :---- | :---- | :---- |
| 1 | View event card | \- | Event title is displayed |
| 2 | Check date and time | \- | Correct date and time are shown |
| 3 | Check status | \- | Status "Open" is displayed |
| 4 | Check location | \- | "Online" or address is shown |

**Negative Test Case**

Test Case ID

TC-04

Title:

Unauthorized user tries to join event

Date Created:

30-03-2026

Author:

Inha Kostrova

Priority: Medium

Preconditions:

1. User is NOT logged in

| Step | Action | Data | Expected Result |
| :---- | :---- | :---- | ----- |
| 1 | Click "Join event" button | \- | System reacts |
| 2 | Check result  | \- | Login popup or access error is displayed |

Test Case ID

TC-05

Title:

Join button is disabled incorrectly

Date Created:

30-03-2026

Author:

Inha Kostrova

Priority: Medium

Preconditions:

1.  Event status is "Open"

| Step | Action | Data | Expected Result |
| :---- | :---- | :---- | :---- |
| 1 | Find an open event | \- | Event is visible |
| 2 | Check "Join event" button | \- | Button should be enabled |
| 3 | (Bug scenario) | \- | Button is disabled without reason |

Test Case ID

TC-06

Title: 

Incorrect counters display

Date Created:

30-03-2026

Author:

Inha Kostrova

Priority: Medium

Preconditions: 

1. Events have likes/comments

| Step | Action | Data | Expected Result |
| :---- | :---- | :---- | :---- |
| 1 | View event card | \- | Counters are displayed |
| 2 | Check values | \- | Values match actual data |
| 3 | (Bug scenario) | \- | Values are incorrect or always 0 |

