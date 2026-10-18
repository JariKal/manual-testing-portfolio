# ALT Zone — UI Manual Test Cases (Portfolio Selection)

**Source:** *ALT Zone testitapaukset (use cases)*, worksheet **Käyttöliittymä Build 267**.  
**Scope:** 15 selected UI checklist scenarios, translated from Finnish and organized for a public testing portfolio.  
**Author contribution:** The portfolio owner has personally performed manual testing across **all areas of the ALT Zone user interface**, and co-designed and documented **parts** of the UI test cases with another tester. This 15-case selection illustrates only a portion of that broader hands-on testing experience. The original workbook does not identify the individual executor of each selected Build 267 result. New testers maintain and execute the checklists against new builds; the portfolio owner and another Test Lead review progress and results.  
**Important:** The statuses below are transcribed from the Build 267 worksheet, **not** results of a new execution. Descriptions are condensed from the original hierarchical checklist; unspecified steps, prerequisites and observations have not been invented.

## Selected test cases — UI Build 267

| ID | Area | Action / condition | Expected outcome from checklist | Build 267 status | Source rows |
|---|---|---|---|---|---|
| UI-01 | First launch | Open privacy policy link during the initial language/privacy flow | ALT Zone privacy policy opens in the device's default browser | Pass | 23–25 |
| UI-02 | Login validation | Leave the username empty or enter invalid characters | Username field turns red and an error message appears | Pass | 37–39 |
| UI-03 | Login interface | Toggle **Show password** | Entered password becomes visible when enabled; visibility toggles back when disabled | Pass | 40, 43–44 |
| UI-04 | Login audio | Tap the sound icon and tap it again | Mute indicator appears and audio is muted; tapping again restores audio | Pass | 50–53 |
| UI-05 | Language selection | Switch from Finnish to English and back | Selected language is highlighted and the game starts in the selected language | Pass | 54–58 |
| UI-06 | Password recovery | Open **Forgot password**, submit an empty value, then an unknown username | Recovery view opens; error messages differ for empty and unknown usernames | Pass | 67–72 |
| UI-07 | Registration validation | Leave registration password empty or make it too short | Field turns red when registering | Pass | 88–90 |
| UI-08 | Main navigation | Tap the player profile icon | Player profile window opens | Pass | 157–158 |
| UI-09 | Tutorial navigation | Select **Tutorial** from the main menu | Tutorial should open; instead the tester is returned to the previous view | **Fail** | 169–173 |
| UI-10 | Battle story navigation | Select **Battle Story** in the story popup | Battle story should open; instead the tester is returned to the previous view | **Fail** | 174–181 |
| UI-11 | Duo lobby invitation | Open online player list and press **Cancel** | Player list should close; Cancel does not work, but tapping outside closes the window | **Fail** | 196–203 |
| UI-12 | Clan search | Enter part of an existing clan name in the search field | Search filters the visible list of clans | Pass | 303–307 |
| UI-13 | Clan search filters | Select a language filter and press **Select** | Language filter works | Pass | 308–316 |
| UI-14 | Clan search filters | Select an activity filter and press **Select** | Activity filter should work; the checklist notes that it does not seem to work and that activity criteria may be undefined | **Fail** | 323–324 |
| UI-15 | Game mode selection | Press the green Play button for the robbery/test mode | Robbery test mode should open | **Not Executed** | 226–227 |

## Selection summary

| Status | Cases in this selection |
|---|---:|
| Pass | 10 |
| Fail | 4 |
| Not Executed | 1 |
| **Total** | **15** |

These numbers describe **only this curated selection**. They must not be presented as totals for the original full UI worksheet. A *Fail* is the recorded checklist outcome, not necessarily a confirmed root cause. *Not Executed* does not mean *Fail*.

## Sample defect observations from the original checklist

- **Tutorial button (row 173):** Returns to the previous view instead of opening the tutorial.
- **Battle Story (row 181):** Returns to the previous view instead of opening the story.
- **Duo lobby Cancel button (row 203):** Does not close the player list; tapping outside the window closes it.
- **Activity filter (row 324):** Marked Fail. The tester notes uncertainty about whether activity criteria exist; the root cause is not established.

Detailed bug reproduction records, severity, device information, and issue IDs are **not** provided by these particular checklist rows. They should not be inferred from the statuses above.

## Manual regression testing and Test Lead workflow

The UI and Battle checklists are used when a new ALT Zone game build is available. Testers execute the relevant checks and update their documented status and observations. The portfolio owner has personally performed manual testing across all UI areas and co-authored parts of the UI checklist with another tester. In the Test Lead role, the owner helps onboard testers, assigns test work, monitors progress, reviews submitted results together with another Test Lead, and communicates with developers.

## Notes for reviewers

- This document is a curated English rendering of authentic historical checklist entries, **not** a newly performed test run.
- Some original entries are nested steps rather than independent formal test cases; the table groups related rows for readability.
- Recorded Build 267 behavior and features may differ from newer builds of ALT Zone.
- No credentials, tokens, personal tester details, or internal issue URLs are included.
