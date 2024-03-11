# Contributing guidelines

Welcome to the Knative UX Working Group (WG)! If you're interested in contributing the User Experience of Knative, you're in the right place! This document
holds information about some of the types of contributions you can make, as well as how to make them.

For more general Knative contributing guidelines, please refer to Knative's overall
[contribution guidelines](https://www.knative.dev/docs/community/contributing/) to
find out how you can help.

## Meetings

Perhaps the best way to get started with the UX WG is to start attending our bi-weekly meetings. The meetings are every other week from 9Am to 10AM ET on Thursday. The
specific weeks they occur on can be seen on the [Knative community calendar](https://calendar.google.com/calendar/embed?src=knative.team_9q83bg07qs5b9rrslp5jor4l6s%40group.calendar.google.com). 
The meeting notes (past, as well as the agenda for the next meeting) can be found [in this google doc](https://docs.google.com/document/d/1VCObP1IQFPDGzGG5KIgytQwX7RrU0tyeB7FGjkY0pPk/edit?usp=sharing). 
The zoom link and password are also at the top of this document. We hope to see you at the next meeting!

There are occasionally other "work session" meetings where some of the designers in the group will hop on a call and work together on an issue. These are arranged in a more ad-hoc manner,
but you can find out all the details about them in [#knative-ux](https://cloud-native.slack.com/archives/C05MW1AT1T8) on the CNCF slack. You will need to [join CNCF slack](https://communityinviter.com/apps/cloud-native/cncf).

## Finding something to work on

In open source, pieces of work are generally termed "issues", so to remain consistent with the rest of Knative and other OSS projects, we use that term as well.
You can find all of the open issues for Knative UX in the [issues tab in the UX repository](https://github.com/knative/ux/issues). These issues are labelled by kind, for example
issues labelled `kind/website` have to do with the design of the website.

When you find an issue which you are interested in, comment `/assign` and a bot will assign the issue to you! Feel free to ask any questions you have either on the GitHub issue or
in the [#knative-ux](https://cloud-native.slack.com/archives/C05MW1AT1T8) slack channel. We are here to help you!

Examples of current issues being worked on include: website color scheme redesign, user survey design and analysis, and other user research methods such as card sorting.

## Designer - developer handoff

Often, the issues being worked on will need a developer to actually program the changes. In these cases, it is up to you to open an issue on the appropriate GitHub repository
detailing the change that needs to be made, after the designs you made have been approved. To understand this process better, let's walk through what your workflow would look 
like if you wanted to work on an issue titled "re-design website buttons".
1. First, you would assign the issue to yourself by commenting `/assign` on the issue
2. Next, you would work on an initial draft of the design.
3. Once you have a design you are happy with or that you want feedback on, you will open a Pull Request to this repository with the artifacts included.
4. The design leads or other contributors in the working group will leave feedback on the design, and possible ask you to make some changes.
5. At the bi-weekly working group meeting, everyone at the meeting will work together to make a final decision on the design. If the group agrees on the changes, it will be merged into the repo.
6. Now, you can go to the repository for the website (knative/docs), and open an issue with the final design asking someone to update the buttons accordingly. If your
change is not for the website and you are not sure which repository it should go to, please ask the WG tech lead for help. 
