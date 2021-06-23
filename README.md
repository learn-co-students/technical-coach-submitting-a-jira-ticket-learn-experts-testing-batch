# Submitting a Jira Ticket

If an issue needs to be escalated to the development team, we file a support ticket through Jira.

## Pre-Escalation Checklist

Since reporting an issue is a heavy load on our development team, there are steps that must be taken before reporting _any_ issue:

- Make sure you or the student (whoever is experiencing the issue) has tried fully refreshing the page, closing the IDE and reopening, logging out of learn.co/canvas and back in, etc.
- For weird issues on a lab, particularly if the student has not yet written any code, it may help to clone a fresh copy of the lab
- If the student is having an issue in the Learn IDE, you should be able to re-create this same issue **in your own Learn IDE**.
- If the issue is related to the IDE, check [here](https://docs.google.com/document/d/1QBE_VOFTu46iKQATk-dfHl-8AJfuMIowOhE9_kbFEU0/edit?ts=5df212e2&pli=1) for solutions
- Browse or search the Zendesk [help center](https://flatironschoolsupport.zendesk.com/hc/en-us) using keywords to see if you can find a solution
- Search the `#tc_support` channel by keyword or error message for any possible solutions
- Do an `@here` in the `#technical-coaches-se` channel to see if any of the other Technical Coaches can help
- Do a quick Google / StackOverflow search for any possible solutions

If you are unable to resolve the issue using the above methods, proceed to report the issue through Jira.

## How to report an issue through Jira
If you are running into an issue that is beyond our team's ability to support, submit a ticket via Jira. 

We prefer that you submit tickets through the Zendesk App, following [these procedures](https://docs.google.com/document/d/1-EjaOf8V0ONLhzzX236FR8cgUeCXR2xiW1yIjwNktqU/edit#bookmark=id.fg7sbt74ij2i)

Alternatively, you can do this directly from this [link](https://flatiron.atlassian.net/projects/TS?selectedItem=com.atlassian.jira.jira-projects-plugin%3Areport-page).

Either will bring you to Jira, where you need to press the `Create`  or `Create Issue` button in the navigation to create the issue.

This will bring up a modal for you to create a ticket based on issue type.

The "Project" for the issue should always be `Flatiron Support Board (LABSBOARD)`.

Select the appropriate issue type and fill in all required fields and any optional fields you are reasonably able to.

When creating your ticket make sure to include:

* Error category (e.g. IDE, Chat, UI, etc.)
* Student, lab, and environment info
  * Include the full name of the student, their Github username, their email (if they do not have a Github username).
  * Include OS version and IDE version (if student is using the IDE)
* A brief description of the issue/error
* What you saw and what you expected to see
* Steps to re-create the error (it's alright if it's not possible to re-create the error on your machine, but at least include the steps needed to create the error on the student's machine)
* All steps taken to try and resolve the error
* Screenshots if available

**Example**
```
Full Name: Michael Jackson
Github Username: HeeHee
Student enail: heehee@email.com
Lab: Has Many Through Forms Rails Lab (https://learning.flatironschool.com/courses/2619/assignments/76664?module_item_id=148220)

OS: OSX Sierra
Environment: Local environment

Issue: Test and PR light won't turn green after passing test and doing learn submit

Thing's we've tried:
- Refresh the page (after everything we tried)
- logged out of Canvas and back in
- Checked Github status
- Deleted forked repo and re forked, ran learn and learn submit
- Deleted local copy and re-cloned, ran learn and learn submit

Attached are some errors in the console while running learn and learn submit. 
```

**Note**: Do not rely on the dev team reading through the chat transcript. Please provide a summary as best you can so they don't have to dig through the chat.

Once you've filled in all the fields, you'll need to set a priority level.

## Priority Level

There are a few different priority levels and it's important to pick the right one. The table below gives a quick overview of issue priorities and their definitions.

| Priority | Definition |
| -------- | ---------- |
| Blocker | Issues that prevent paid users from learning, or sitewide issues that affect all users. For example: a paid user's IDE not working or they can't access their track or billing. **Use with caution**. |
| High | A paid student has an issue that is causing a poor experience. For example: a paid user's lights on `learn.co` or checkmarks on canvas aren't updating.
| Medium | An issue that needs to be addressed and may be causing a poor experience but does not need to be fixed for a few business days. For example, a paid user has Slack invitation issues, or can't switch their blog type.
| Low | An issue that would be nice to fix, but can be addressed down the road during a clean up week. For example, visual quirks, feature requests or improvements; free user has has a problem with Slack or their progress data is incorrect.

**Raising a blocking issue will alert the entire Flatiron staff. Use ONLY for critical issues.**

[Use this spreadsheet to determine which priority level you should use.](https://docs.google.com/a/flatironschool.com/spreadsheets/d/1_yr-CsT0hIfSEcz9vv9yjkRGWQLeKmG40SNjywphoOc/edit?usp=sharing)

Note that the spreadsheet also gives expected turnaround times for each priority level, as well as suggested snippets to share with students once the ticket has been submitted. Students will understandably have questions about how long it will take for their issue to be addressed, so keep them in the loop!

**Note: If the student can move forward (go to the next lesson for now), then it is *not* a blocking issue.**

## Resources

* [Ticket Priority Levels](https://docs.google.com/a/flatironschool.com/spreadsheets/d/1_yr-CsT0hIfSEcz9vv9yjkRGWQLeKmG40SNjywphoOc/edit?usp=sharing)
* [Submitting a Jira Ticket Video Walkthrough](https://www.youtube.com/watch?v=9LC_G99xHlY&feature=youtu.be)
