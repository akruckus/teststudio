---
title: Analyze the Results
page_title: Analyze Test and Test List Results
description: "View the results from your execution and analyze the passed and failed steps."
position: 3
---
# Analyze The Results #

There are many ways to analyze the test and test list results in Test Studio. This information can be used to see which stepst and tests were executed and what was the outcome for each of 
them. In case the test has failed, you can review the results and try to quickly fix it. You can find additional details below:

- [Execution log](#execution-log)
- [Analyze test list results](#analyze-test-list-results)
- [Step failure details](#step-failure-details)
- [Application log](#application-log)
- [Visual debugger](#visual-debugger)

## Execution Log ##

The <a href="/general-information/test-results/analyze-quick-run-results" target="_blank"> quick execution log</a> is available in the test view after a [quick test execution](/general-information/test-execution/quick-execution). It contains details about the latest test run and you can open it by clicking on the **View Log** button.

## Analyze Test List Results ##

The *Results* tab contains results for all locally and remotely executed test lists. There you can <a href="/general-information/test-results/analyze-test-list-results" target="_blank">analyze the executions</a>, drill down to the individual test step and go back up to the main test list level for each execution.

## Step Failure Details ##

The sucecssfully executed steps will be marked with ![pass](/img/getting-started/analyze-the-results/fig01.png) and the failed steps are marked with ![step failure icon](/img/getting-started/analyze-the-results/fig02.png). You can double-click on the icon of a failed steps to load the <a href="/general-information/test-results/step-failure-details" target="_blank">**Step Failure Details**</a> dialog. You can see the reason for the failure, a screenshot from the moment of failure and <a href="/troubleshooting-guide/troubleshooting-tools-tg/using-the-dom-on-failure" target="_blank">the page DOM tree</a>.

![Test](/img/getting-started/analyze-the-results/fig03.png)

## Application Log ##

The <a href="/troubleshooting-guide/troubleshooting-tools-tg/using-the-application-log" target="_blank">application log</a> is a list of messages logged by Test Studio throughout the tool usage and bring information for the performed actions in Test Studio. It is usually used if there are unexpected errors, crashes, or a recommended configuration in the project cannot be accomplished

## Visual Debugger ##

The <a href="/troubleshooting-guide/troubleshooting-tools-tg/using-the-visual-debugger" target="_blank">visual debugger</a> has different options for debugging a test while its execution is paused. It is used if the test does not behave as expected, especially when it is not clear at which point the issue occurred.

<div><a href="/getting-started/first-project">Go to <strong>Your First Project</strong></a><a style="float:right" href="/getting-started/next-steps">Go to <strong>Next Steps</strong></a></div>