---
layout: post
title: "[006] What happens during a code review? (Reviewer perspective)"
author: Mikołaj Korbanek
date: 2022-12-16
tags: CodeReview
---

Welcome in, the next article in our series about Code review. In this blog post, we will talk what to expect when you have to attend a code review as a reviewer.

There are serial points that are going to happen. Let's start with it!

## Receiving a Notification

From the perspective of the reviewer, code review involves several steps. First, the reviewer will receive a notification that there is code ready for review. This may come in the form of an email, a notification in a team collaboration tool, or a request in a code review tool.

## Checking Out the Code
This step depends on a source control tool that you are using.

There are two approaches:

### Online tool

Code review tools can be a valuable asset for reviewers, as they provide a convenient way to view the code and leave comments. If you don't know any app, you can check out our [previous post]({% post_url 2022-12-15-04-Tools-and-Platforms-for-Enhanced-Collaboration-in-Code-Review %}). This can be especially useful for reviewers who may be working remotely or on a different machine than the one with the code checked out.

Using these web-based code review tools, reviewers can easily view the code and its changes, leave comments and suggestions, and collaborate with the original developer to ensure that the code is of high quality. Additionally, many code review tools also provide features such as code highlighting and automatic error checking, which can help reviewers identify potential issues more quickly and easily.

### Local machine

In this approach, the reviewer will need to check out the code that needs to be reviewed. This usually involves pulling the code from the version control system, such as Git, and checking it out onto their local machine.

## Conducting the Review

Once we have access to code, the reviewer can start the review process. This typically involves reading through the code carefully, looking for any issues or problems. Some common things that reviewers look for include:

- Errors or bugs
- Inefficient or poorly-written code
- Security vulnerabilities
- Code that is difficult to understand or maintain

As they go through the code, the reviewer will typically use a code review tool to leave comments or suggestions for the original developer. These comments may include suggestions for how to improve the code, questions about why certain decisions were made, or concerns about potential problems.

> Sometimes during the review it is worthwhile to download the code anyway, in order to manually test whether the solution works as it should. Not everything can be seen by reading the code.

## Submitting Feedback
Once the review is complete, the reviewer will typically submit their feedback to the original developer. The developer can then address any concerns or issues raised in the review and resubmit the code for further review if necessary.

## Conclusion

Overall, code review is an important part of the software development process that helps ensure that the code is of high quality and follows the team's coding standards. From the perspective of the reviewer, it involves carefully reading through the code, looking for any potential issues, and providing feedback to the original developer.
