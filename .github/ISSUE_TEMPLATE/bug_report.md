---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: diablodale

---

## Description

Provide a clear and concise description of your issue.

> :warning: Do not disclose private information anywhere in this issue.

## Setup

* Computer hardware description: CPU, memory, storage, GPU, etc.
* Operating system version. Run `winver` and provide the complete "Version xxxx (build xxxxxx)".
* Cycling '74 Max version. Is Max registered?
* dp.kinect2 plugin version. Get it from the Max console when you load the plugin.
* ...and any remaining setup/configuration.

## Reproduce steps

Detail every step needed to reproduce your issue.
Set `@verbose 1` on dp.kinect2 to receive additional debug information in the Max console.
I recommend you create a small patch that demonstrates the problem. Attach that patch to this issue.

For example...

1. Start Max 7.
2. Open the dp.kinect2 help patch
3. Click on the xyz tab
4. Press blue button
5. Click the checkbox labeled "start"
6. ...

## Result

What result did you *actually* get?
Please provide screenshots when possible.

## Expected

What result did you *expect* to get?

## Workarounds

Did you discover any workarounds? What are they?

## Max console output

When you set `@verbose 1` as requested above, additional debug messages were sent to the Max console.
Please replace the list below with those messages from your Max console.

```
1. First group of messages which provide version
   information and settings.
2. All diagnostic messages related to your issue.
   They are often yellow or red.
```
