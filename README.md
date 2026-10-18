# Manual Software Testing Portfolio – ALT Zone

This portfolio demonstrates my practical experience in **manual software testing, test case design, regression testing, bug reporting, and test coordination**.

The examples are based on real testing activities from **ALT Zone**, a multiplayer mobile game developed by Psyche's Royale Gaming ry.

I have worked as both a **Software Tester and Test Lead** in the project, combining hands-on testing with responsibilities related to guiding testers, coordinating tasks, and reviewing test results.

## Project Overview

ALT Zone is a multiplayer mobile game that includes user interface functionality, player interactions, and multiplayer battle features.

Manual testing is an important part of the development process. Testers use documented test cases to check functionality in new game builds, record results, identify defects, and verify changes.

The testing documentation is maintained as the game develops, allowing test cases to be updated when functionality changes.

## My Role and Responsibilities

### Manual Software Testing

I have performed manual testing across all areas of the ALT Zone user interface and participated in testing Battle functionality.

My practical testing experience includes:

- Testing application functionality and user flows.
- Checking UI elements, navigation, menus, and interactions.
- Testing Battle-related functionality and multiplayer features.
- Performing manual regression testing on game builds.
- Identifying, reproducing, and reporting software defects.
- Verifying functionality after changes and fixes.
- Documenting and reviewing test results.

### Test Case Design and Documentation

I contributed to developing the manual test case documentation together with another tester.

My contributions include:

- **Battle:** Independently designing and documenting the complete Battle test case section.
- **User Interface:** Designing and documenting selected UI test cases in collaboration with another tester.
- Organizing test cases into functional areas and test flows.
- Supporting repeatable manual testing across different game builds.
- Maintaining and improving test documentation as functionality evolves.

### Test Lead Responsibilities

I have also worked as a Test Lead in the ALT Zone project.

My responsibilities include:

- Onboarding and training new testers.
- Explaining testing procedures and test documentation.
- Assigning and coordinating testing tasks.
- Monitoring testing progress.
- Reviewing test execution results and documentation together with another Test Lead.
- Communicating with developers about testing activities, findings, and reported issues.

New testers currently execute and maintain the test cases as part of the project's ongoing testing process. The Test Leads review testing progress and results.

## Manual Testing Examples

This repository contains selected test cases from actual ALT Zone testing documentation.

The examples are based on **Build 267** and demonstrate how manual testing activities and results are documented.

### [Battle Manual Test Cases – Build 267](ALT_Zone_Battle_Manual_Test_Cases.md)

A selection of 20 test cases from the Battle testing documentation.

The examples cover different areas of Battle functionality, including room creation, matchmaking, battle startup, user interface controls, and gameplay mechanics.

**Selected test case results:**

| Status | Count |
|---|---:|
| Pass | 18 |
| Fail | 2 |
| Total | 20 |

**Complete Battle testing summary for Build 267:**

| Status | Count |
|---|---:|
| Pass | 109 |
| Fail | 3 |
| Not Executed | 16 |
| Total | 128 |

I independently designed and documented the Battle test case section. The selected results represent the documented testing outcomes for the build, not exclusively tests executed by me.

### [UI Manual Test Cases – Build 267](ALT_Zone_UI_Manual_Test_Cases.md)

A selection of 15 test cases from the user interface testing documentation.

The examples cover application startup, language selection, authentication, password recovery, navigation, clan search, and other UI functionality.

**Selected test case results:**

| Status | Count |
|---|---:|
| Pass | 10 |
| Fail | 4 |
| Not Executed | 1 |
| Total | 15 |

I have personally performed manual testing across all areas of the ALT Zone user interface and contributed to designing selected UI test cases with another tester.

The documented Build 267 results are presented as project testing results rather than exclusively my individual executions.

## Manual Regression Testing Workflow

The ALT Zone testing process uses documented test cases to support testing across game builds.

The general workflow includes:

1. **New build available:** Testers receive a new version of the game for testing.
2. **Test execution:** Testers work through relevant UI and Battle test cases.
3. **Result documentation:** Test results are recorded using statuses such as Pass, Fail, and Not Executed.
4. **Defect investigation:** Unexpected behavior is investigated and reported.
5. **Test case maintenance:** Test documentation is updated when game functionality changes.
6. **Test Lead review:** Test Leads monitor progress and review the recorded results.
7. **Developer communication:** Testing findings and issues are communicated to the development team.

This process supports repeatable testing and provides visibility into testing progress between builds.

## Test Result Statuses

| Status | Description |
|---|---|
| **Pass** | The test was executed and the functionality worked as expected. |
| **Fail** | The test was executed and unexpected behavior or a defect was observed. |
| **Not Executed** | The test was not executed, for example because it was not yet tested or could not be tested. |

A failed test does not automatically indicate that the entire feature is unusable. It records a specific test outcome requiring investigation or follow-up.

## Real Bug Report Examples

The following examples are based on real defects I reported during ALT Zone development. Each example includes a link to the original GitHub issue.

### [Bug #1462 – UI Popup Overlaps with Chat](ALT_Zone_Bug_Report_1462.md)

A user interface layout issue where a customization popup was partially covered by the chat window.

This report demonstrates:

- Identifying and reproducing a UI defect.
- Documenting steps to reproduce the problem.
- Describing expected and actual behavior.
- Communicating findings to developers.

The developer documented a fix and referenced a commit in the original issue.

**Original report:** [ALT Zone Issue #1462](https://github.com/Alt-Org/Altzone/issues/1462)

### [Bug #1507 – Character Selection Causes Battle to Freeze](ALT_Zone_Bug_Report_1507.md)

A Battle functionality issue where selecting specific characters caused the game to become stuck during the Battle startup flow.

This report demonstrates:

- Identifying a gameplay-blocking defect.
- Documenting the affected character selections.
- Reporting unexpected Battle behavior.
- Supporting investigation of a functional issue.

The issue was closed as completed. Detailed fix implementation and personal retesting are not documented in the original issue.

**Original report:** [ALT Zone Issue #1507](https://github.com/Alt-Org/Altzone/issues/1507)

### [Bug #1309 – Missing Clan Language Icons](ALT_Zone_Bug_Report_1309.md)

A user interface issue involving missing language selection icons.

The discussion helped clarify which language options were intended to be available in the game.

This report demonstrates:

- Identifying inconsistencies in UI functionality.
- Reporting missing interface elements.
- Communicating with developers.
- Clarifying expected functionality through issue discussion.

**Original report:** [ALT Zone Issue #1309](https://github.com/Alt-Org/Altzone/issues/1309)

These reports demonstrate my practical experience in defect identification, documentation, and communication.

Closed issues do not automatically prove that every defect was successfully retested, and I do not claim to have personally verified every fix.

## Bug Reporting and Investigation

My manual testing experience also includes investigating and reporting software defects.

This involves:

- Identifying unexpected application behavior.
- Reproducing defects when possible.
- Describing observed and expected behavior.
- Documenting findings for developers.
- Communicating about reported issues.
- Verifying fixes through further testing when applicable.

The original GitHub issues provide examples of how testing findings are communicated within the development project.

## Skills Demonstrated

This portfolio demonstrates practical experience in:

- Manual functional testing
- Mobile game testing
- User interface testing
- Multiplayer game testing
- Test case design and documentation
- Manual regression testing
- Test execution and result tracking
- Bug reporting and investigation
- Tester onboarding and guidance
- Test task coordination
- Reviewing testing progress and results
- Communication with software developers

## Related Testing Projects

I also maintain separate API testing portfolios:

- [Postman & Newman API Testing](https://github.com/JariKal/postman-newman-api-testing) – API regression testing, automated collection execution, and reporting.
- [ALT Zone API Testing with Robot Framework](https://github.com/JariKal/altzone-api-testing) – Automated API testing with authentication and dynamic identifiers.
- [Robot Framework API Testing Practice](https://github.com/JariKal/robot-framework-api-testing) – REST API testing practice using JSONPlaceholder.

These projects complement my manual testing experience and demonstrate my ongoing development in test automation.

## About the Portfolio

The examples are selected from real ALT Zone test documentation and reorganized for portfolio presentation.

The original testing documentation is maintained separately as part of the game's development and testing process.

The material is shared with permission. This repository represents my testing experience and contributions and is not an official release or complete test suite for the ALT Zone project.

## Career Interests

I am interested in opportunities in **Software Testing and Quality Assurance**, particularly manual testing, API testing, and QA roles involving test coordination.

I want to continue developing my test automation skills while applying my practical experience in manual testing, defect investigation, and supporting testing teams.
