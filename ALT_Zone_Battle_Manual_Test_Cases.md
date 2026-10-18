# ALT Zone — Battle Manual Test Cases (Portfolio Selection)

**Source:** *ALT Zone testitapaukset (use cases)*, worksheet **Battle Build 267**.  
**Scope:** Selected entries from the original Finnish battle testing checklist; translated and organized for a public portfolio.  
**Author contribution:** The Battle test case section was designed and documented by the portfolio owner. Ongoing execution and maintenance are performed by the testing team, with reviews by the Test Leads.  
**Important:** This is an illustrative selection, not the complete regression suite. Statuses below are transcribed from the Build 267 worksheet; they do not represent a new test run. Several cases combine adjacent hierarchical checklist rows into a readable scenario. No extra testing steps or measured results have been invented.

## Test execution snapshot — Build 267

| Status | Count in original Battle worksheet |
|---|---:|
| Pass | 109 |
| Fail | 3 |
| Not Executed | 16 |

In the source document, **Not Executed** can mean that a feature was not yet available for testing. The totals are the source worksheet's own summary, not a recount of the selection below.

## Selected battle test cases

| ID | Area | Action / test condition | Expected outcome (from source checklist) | Build 267 status | Source rows |
|---|---|---|---|---|---|
| BTL-01 | Custom battle setup | Browse available venues / rooms | Open, created rooms are displayed | Pass | 6–7 |
| BTL-02 | Custom battle setup | Use the **All** room filter | Rooms are sorted | **Fail** | 8–9 |
| BTL-03 | Create room | Select **Create Room** | Room creation screen opens | Pass | 10–11 |
| BTL-04 | Create room | Choose venue using left/right arrows | Venue selection responds to the arrows | Pass | 12–13 |
| BTL-05 | Create private room | Select the private-room checkbox | Password entry field opens | Pass | 16–18 |
| BTL-06 | Create room | Press **Create Room** after setup | Room is created and battle-start view opens | Pass | 24–25 |
| BTL-07 | Start battle | Press **Start** | Battle-start pop-up shrinks; subsequent battle views open | Pass | 32–37 |
| BTL-08 | Leave lobby | Press **Leave** in battle-start view | Battle-start view closes and player leaves the room | Pass | 38–40 |
| BTL-09 | Close lobby view | Press **X** in battle-start view | View closes, but player remains in the room waiting for players | Pass | 41–43 |
| BTL-10 | Matchmaking | Press the stop-search button | Matchmaking search stops | Pass | 46–47 |
| BTL-11 | Matchmaking | Close matchmaking window using **X** | Window closes but player remains in matchmaking queue | Pass | 48–49 |
| BTL-12 | Matchmaking | Press **Cancel** | Player is removed from matchmaking queue | Pass | 56–57 |
| BTL-13 | Duo lobby | Invite online players when no clan members are online | Error message is shown | Pass | 61–62 |
| BTL-14 | Duo lobby | Invite online players when clan members are online | List of available players opens | Pass | 61, 63 |
| BTL-15 | Duo lobby | Press **Cancel** in the player list | List should close through its Cancel button; source notes that clicking outside was required | **Fail** | 64 |
| BTL-16 | Duo lobby | Press **Start** with only one player in lobby | Error message is shown | Pass | 66–67 |
| BTL-17 | Battle mechanics | Emotion ball strikes side wall | Ball bounces back into play | Pass | 93–96 |
| BTL-18 | Battle mechanics | Emotion ball strikes rear wall | A piece breaks off the wall, ball speed resets, and tears become collectible | Pass | 97–99 |
| BTL-19 | Battle mechanics | Emotion ball hits a player's shield | Ball direction depends on shield orientation; shield HP decreases and ball speed increases | Pass | 101–105 |
| BTL-20 | Battle outcome | Emotion ball passes through rear wall toward the stone character's soul | Game ends | Pass | 111–112 |

## Example defect observations

**Room sorting — Build 267:** The original checklist marks *Lajittelee huoneet* (“Sorts rooms”) as **Fail** (source row 9). No detailed reproduction steps or actual sorting behavior are documented in that row. A separate bug report would be needed for those details.

**Duo player-list Cancel button — Build 267:** The checklist marks the Cancel button as **Fail** and states: *“Pitää painaa ohi ikkunasta että ikkuna sulkeutuu”* — the tester must click outside the window to close it (source row 64).

## How this checklist is used

New testers work through the UI and Battle checklists against new game builds and update the documented outcomes. The portfolio owner and another Test Lead review progress, execution, and changes, and coordinate with developers. The larger source workbook tracks results over multiple builds; this public selection is only one historical snapshot.

## Notes for reviewers

- Entries above are a curated translation of the original team's hierarchical test checklist, **not** newly authored or independently re-executed test cases.
- The source worksheet is a **checklist-style** test specification: some steps, setup conditions, and expected results are implicit in the hierarchy. This document preserves those limitations rather than inventing missing prerequisites.
- Build 267 includes historic 2v2 and related terminology; the portfolio demonstrates testing of that build, **not a claim about current ALT Zone design**.
- Test environment credentials, internal issue links, and raw API responses are intentionally excluded.
