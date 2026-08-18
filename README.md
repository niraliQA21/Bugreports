# Bug Reports

## Overview

This repository contains bug reports used to document, track, and manage issues found during testing or regular application usage. Each bug report provides enough information for developers and testers to reproduce, investigate, and resolve the issue.

## Objectives

* Clearly document software defects.
* Make bugs easy to reproduce.
* Provide sufficient information for investigation.
* Track the progress of reported issues.
* Verify that fixed bugs are resolved successfully.
* Prevent recurring issues through proper documentation.

## Bug Report Structure

Each bug report should include:

| Field                  | Description                                          |
| ---------------------- | ---------------------------------------------------- |
| **Bug ID**             | Unique identifier for the bug                        |
| **Title**              | Short and descriptive summary of the issue           |
| **Environment**        | Browser, OS, device, version, or build information   |
| **Preconditions**      | Requirements before reproducing the bug              |
| **Steps to Reproduce** | Actions required to reproduce the issue              |
| **Test Data**          | Input data used when reproducing the bug             |
| **Expected Result**    | Behavior that should occur                           |
| **Actual Result**      | Behavior that actually occurs                        |
| **Severity**           | Impact of the bug on the application                 |
| **Priority**           | Urgency with which the bug should be fixed           |
| **Attachments**        | Screenshots, videos, logs, or other supporting files |
| **Status**             | Current state of the bug                             |

## Bug Severity

### Critical

The issue causes a complete system failure, data loss, security problem, or prevents the application from being used.

### High

The issue significantly affects an important feature or workflow and has no reasonable workaround.

### Medium

The issue affects functionality but a workaround is available or the impact is limited.

### Low

The issue has minimal impact, such as a minor UI, text, or visual problem.

## Bug Priority

* **P1 — Urgent:** Should be fixed immediately.
* **P2 — High:** Should be addressed as soon as possible.
* **P3 — Medium:** Can be scheduled for a regular release.
* **P4 — Low:** Can be fixed when resources are available.

## Example Bug Report

**Bug ID:** BUG-001
**Title:** Login button does not respond to valid credentials

**Environment:**

* Browser: Chrome
* OS: Windows
* Application Version: 1.0.0

**Preconditions:**

* A registered user account exists.
* The login page is accessible.

**Steps to Reproduce:**

1. Open the login page.
2. Enter a valid username.
3. Enter the correct password.
4. Click **Login**.

**Expected Result:**
The user should be successfully logged in and redirected to the dashboard.

**Actual Result:**
Nothing happens after clicking the **Login** button.

**Severity:** High
**Priority:** P1

**Status:** Open

## Bug Status

* **Open** — Bug has been reported and requires investigation.
* **In Progress** — Bug is currently being worked on.
* **Fixed** — A fix has been implemented.
* **Ready for Testing** — Fix is ready for verification.
* **Verified** — Tester has confirmed that the issue is resolved.
* **Reopened** — The issue still occurs after being marked as fixed.
* **Closed** — Bug has been successfully resolved and verified.
* **Won't Fix** — Issue will not be addressed.
* **Duplicate** — The issue has already been reported.

## Reporting Guidelines

When creating a bug report:

1. Use a clear and descriptive title.
2. Provide exact steps to reproduce the issue.
3. Include expected and actual results.
4. Mention the environment and application version.
5. Include relevant screenshots, videos, logs, or error messages.
6. Assign an appropriate severity and priority.
7. Avoid combining multiple unrelated issues in one report.
8. Verify that the bug has not already been reported.

## Verification

After a bug is fixed:

1. Reproduce the original scenario.
2. Confirm that the reported issue no longer occurs.
3. Run relevant regression tests.
4. Verify that the fix does not introduce new issues.
5. Update the bug status to **Verified** or **Closed**.
