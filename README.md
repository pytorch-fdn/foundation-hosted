# PyTorch Ecosystem

![PyTorch Ecosystem](https://raw.githubusercontent.com/pytorch/pytorch/0d4cedaa47c7ee22042eb24e87eb3cfe95502404/docs/source/_static/img/pytorch-logo-dark.svg)

This repository is designed to allow projects seeking to join the PyTorch Foundation Ecosystem as a project to submit their applications. It is still a work in progress and we welcome PRs on this repo to automate assignments, improve the process, etc.  If you have any questions, please post a message to the [TAC Slack Channel](https://pytorch.slack.com/archives/C0808K2MN95).
For information on the  process please check out the [details on our application process below](#how-applications-are-reviewed).

## How to apply

Applying is as easy as 1-2-3!

1. Open a new [Ecosystem Application](https://github.com/pytorch/ecosystem/issues/new?assignees=&labels=New&projects=&template=application.yml&title=%3CProject+Name%3E?assignees=&labels=New&projects=&template=application.yml&title=%3CProject+Name%3E) using the linked issue form.
1. Complete all sections of the form.
1. Submit the issue.

## What's next?

Your project's application is placed in the backlog for triaging. You can view the status of your application and others at any time by checking out our [Project Board](https://github.com/orgs/pytorch/projects/85).

As we approach Ecosystem review meetings, PyTorch staff will move applications to the "in-progress" column on the Project Board (number dependent on how many can be reviewed in a given meeting). At this point, the Technical Advisory Committee will ask questions, seek to learn more, and make a decision on the project.  

### Community Comments on Applications

The TAC welcomes and appreciates community members support and exploration in surfacing items for technical consideration as part of application process because it allows the TAC to have a more comprehensive perspective on each projects' potential and supports our understanding about these projects. 

### The TAC's review meeting

When the TAC meets to review applications, your application will be pulled up and discussed. Your application may receive one of several statuses:

* `New` - It is a brand new application and is in the backlog for an upcoming review.
* `Approved` - The application has been reviewed and been approved by the TAC. The issue will be closed.
* `Declined` - The application has been reviewed and been declined by the TAC. The comments on the issue will reflect the TAC decision and the issue will be closed.
* `Need-Info` - The application has been reviewed and requires more information in order for the TAC to further discuss the application.  For instructions on what to do, please jump down to [Need-Info](#need-info).
* `TAG-Assigned` - The application has been reviewed and the TAC would like a TAG to review or consult with the project prior to further discussions.  For instructions on what to do, please jump down to [TAG-Assigned](#tag-assigned).
* `Postponed` - The application has been reviewed and the TAC has determined the project (as it exists at time of review) is not ready for inclusion within the PyTorch. For instructions on what to do, please jump down to [Postponed](#postponed)
* `Returning` - The application has been reviewed previously, was affixed a `Need-Info` or `TAG-Assigned` label, and that work has been completed and is ready for re-review.  For instructions on what to do, please jump down to [Returning](#returning).

### Label statuses defined

Removing, updating, and adding labels as well as updating the project board are the responsibility of the TAC and PyTorch staff.  Please refrain from adding additional labels.

#### New

The application is new and placed in the backlog.

#### Approved

The application has been approved.

#### Declined

The application has been declined.  The reasons for decline will be provided in the comments of the issue.  

#### Need Info

If your project is assigned a `Need-Info` label, the TAC will comment on the issue with the specific additional information needed. 

Please provide the additional information requested as a comment on the issue with links as appropriate. Once you have done this, please add the below text to your comment so the TAC and staff know to update the issue:
`Completed info, project is Returning`

This lets the TAC know the project is ready to be reviewed again. A TAC member or staff will remove the `Need-Info` label and affix `Returning` where it will then be removed from the `Waiting` status and placed in the `Upcoming` status for discussion at the next meeting.

#### TAG Assigned

If your project is assigned an `TAG-Assigned` label, the TAC will comment which TAG(s) and provide specific details on what is requested. The TAG Co-Chair(s) will be tagged on the issue. Depending on the details of the comment, the TAG or the project will update the issue with a comment containing any pertinent information. This may include links to a presentation recording, as summary of a discussion with the TAG, or recommendations.

Once a comment has been added, please add the below text to your comment so the TAC and staff know to update the issue:
`Completed TAG review, project is Returning`

This lets the TAC know the project is ready to be reviewed again. A TAC member or staff will remove the `TAG-Assigned` label and affix `Returning` where it will then be removed from the `Waiting` status and placed in the `Upcoming` status for discussion at the next meeting.

##### TAG(s)

If the issue is affixed the `TAG-Assigned` label and you have been tagged on the issue as a TAG co-chair, please review the comments for the specific asks regarding the project. When completed, please provide a comment containing any pertinent information. This may include links to a presentation recording, as summary of a discussion with the TAG, or recommendations. Please work with the project to coorindate who will be updating the issue.

Once a comment has been added, please add the below text to your comment so the TAC and staff know to update the issue:
`Completed TAG review, project is Returning`

This lets the TAC know the project is ready to be reviewed again. A TAC member or staff will remove the `TAG-Assigned` label and affix `Returning` where it will then be removed from the `Waiting` status and placed in the `Upcoming` status for discussion at the next meeting.

#### Postponed

 If the issue has been affixed with the `Postponed` label it will be closed as the TAC has determined the project at the time of discussion is not ready for inclusion into the PyTorch. There will be a comment on the issue that annotates the expectations in order for the project to be re-reviewed by the TAC. Depending on the status and details, there are a few options to be re-reviewed. For information on review ordering for postponed projects, plese refer to the [Review Order section](#review-order).

##### Returning for review after being postponed

a. If the project has had substantial changes to the original information provided, open a new issue and link to the previous issue in the `Additional information` question (last question on the form). The project will be reviewed as if it were a new project applying but retain the historical context of the previous review to assist in evaluation.

b1. If the project has had *no* substantial changes, the originator of the issue may reopen it and provide a brief status update that addresses the TAC closure comments with a comment `Revisit Ready`. The TAC or staff will apply the `Returning` label and place the issue in the `Upcoming` status for discussion at the next meeting.

b2. If the individual seeking to reopen the issue is NOT the originator of the issue AND the project has had no substantial changes, provide a brief status update that addresses the TAC closure comments. The TAC or staff will reopen the issue and apply the `Returning` label and place the issue in the `Upcoming` status for discussion at the next meeting.

#### Returning

Issues affixed with the `Returning` label are placed in the In Review status on the project board for an updated discussion at the next available meeting.

## How applications are reviewed

### Frequency

The TAC reviews applications approximately once every 2 months.

### Quantity

The TAC attempts to work through approximately 7-10 applications per session. How many are actually reviewed in a session varies greatly between each session. Every project is unique and may warrant different areas of attention to be elevated for more in-depth discussion, depending on the nature and function of the project.

Each TAC member prepares for these sessions by performing an independent review of those projects scheduled for discussion at the next session prior to that session. They'll keep their notes on hand for when the project is up for discussion.

### Review order

Applications are traditionally reviewed in a First In, First Out (FIFO) ordering as they appear on the **🏗 Upcoming** Column of the project board by their corresponding issue number. The only exception is where projects are `Returning` for review. Projects that are `Returning` are prioritized for re-review as they had previously been subject to a review and have completed their outstanding asks. In cases where a project was `Postponed` and has substantial changes since last review, a new issue is opened, linked to the previous, and reviewed as a new application. 

Applications are moved from `New` to `in review` approximately two weeks prior to the next scheduled session by the TAC or support staff.

### Discussions

During the course of the session, the TAC will actively discuss the project based on the information provided in the issue as well as other observations the TAC has about the project. Those observations vary greatly and may be subject to each TAC member's area of domain expertise, personal experience, community feedback, or other factors. During the course of active discussion, the TAC may identify areas the project needs to work on, complete, or allow to happen that could inhibit its acceptance into the PyTorch. These areas will be captured succinctly and affixed the corresponding label. The issue will also receive a comment that details the additional areas that correspond with the label. The TAC comment may be formatted as a checklist or may be presented as text.

## Voting

The TAC members will then vote on the project acceptance with a simple majority vote, one vote per premier organization member.  

## Acceptance or Decline 

Once the voting is complete, the project is labeled with the status as accepted or declined based on the voting status.  Projects will have information in the issue that describes feedback provided by the TAC.  

## Decline and Reapplication

A project that has been declined may reapply for acceptance once the comments raised by the TAC as the reasons for the decision have been addressed. 



