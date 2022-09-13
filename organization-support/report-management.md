---
description: Report Actions
---

# Report Management

Hackers can submit vulnerabilities to your program through [submitting reports](../hacker-support/submitting-reports.md) option. You can manage all incoming reports through your Inbox by taking the flowing actions:

* [Add comments](report-management.md#add-comments)
* [Close a Report](report-management.md#close-a-report)
* [Request more details](report-management.md#request-more-details)
* [Change the state of report as _Triaged_](report-management.md#change-the-state-of-report-as-triaged)

![report\_actions](https://www.scorelab.org/bugzero-supports/assets/images/report\_actions.PNG)

### Add Comments <a href="#add-comments" id="add-comments"></a>

You can add comments on the reports to communicate with hackers or team members and/ or make specific notes regarding submitted reports.

To add a comment:\
1\) Go to the bottom of the report above the comment box.\
2\) Make sure the action picker is set to **Add comment**.\
3\) Click the **Add Comment** button

![report-actions-2](https://www.scorelab.org/bugzero-supports/assets/images/report\_comment.PNG)

### Change the state of report as **Triaged** <a href="#change-the-state-of-report-as-triaged" id="change-the-state-of-report-as-triaged"></a>

You can change the state of a report as _Triaged_. That’s mean the report has passed the initial validation and is pending resolution. When you select triage, you can enter the reference ID to your integration in the Reference ID field.

To change the state of a report:\
1\) Go to the bottom of the report.\
2\) Change the action picker to **Triaged** from the drop-down.\
3\) Add a new reference ID for the report.\
4\) Click **Change Report State** button.

![report-action-3](https://www.scorelab.org/bugzero-supports/assets/images/report\_triaged.PNG)

### Request more details <a href="#request-more-details" id="request-more-details"></a>

You can request more details if you needs more information from the hacker before proceeding. For that you can send back report to the hacker by applying this action to the report.

To request more details:\
1\) Go to the bottom of the report above the comment box.\
2\) Select **Need More Details** in the action picker.\
3\) Click **Request More Details** button.

![report-action-4](https://www.scorelab.org/bugzero-supports/assets/images/report\_details.PNG)

### Close a Report

You can close a report to mark that it’s either:\


![](https://www.scorelab.org/bugzero-supports/assets/images/diagram.png)

| State      | Details                                                                                                                                                                                                |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Fixed      | The report is valid and acceptable.                                                                                                                                                                    |
| No Problem | The reported vulnerability doesn’t needed an immediate action or a fix.                                                                                                                                |
| Duplicate  | This issue has already been reported. Programs can build trust by attributing the issue to its original discoverer and linking it to a previous report or including other details about its discovery. |
| Irrelevant | The report doesn’t contain a valid issue and details regarding the vulnerability.                                                                                                                      |
| Spam       | The report is invalid because the hacker didn’t describe a legitimate security vulnerability.                                                                                                          |

To close a report:\
1\) Go to the bottom of the report above the comment box.\
2\) Select **Close report** in the action picker.\
3\) Choose the status of the report which reasoned to the close report.\
4\) Click **Close report** button.

![report-action-5](https://www.scorelab.org/bugzero-supports/assets/images/report\_close.PNG)

### Grant Rewards

After a report is closed you can grant rewards to the hacker:\
1\) Go to the bottom of the report above the comment box.\
2\) Select **Grant Rewards** in the action picker.\
3\) Select the reward type:

* Bounty - You can enter amount of the bounty
* Swag - You can select to reward the swag

![Rewards](<../.gitbook/assets/image (6).png>)
