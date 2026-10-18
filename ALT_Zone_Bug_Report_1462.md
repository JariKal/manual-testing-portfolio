# Bug Report Example – UI Popup Overlaps with Chat (Issue #1462)

**Project:** ALT Zone – multiplayer mobile game  
**Area:** User interface / My Booth editing popup  
**Original report:** [Alt-Org/Altzone Issue #1462](https://github.com/Alt-Org/Altzone/issues/1462)  
**Reported by:** [JariKal](https://github.com/JariKal)  
**Reported on:** April 23, 2026  
**GitHub issue status:** Closed as completed on April 23, 2026

## Issue Summary

The popup used to edit the player's own booth is partially obscured by the chat interface. The original report raised a possible scaling issue as a question; the root cause was not established in the report.

## Affected Area

Inventory → My Booth → Edit popup.

## Steps to Reproduce

1. Open **Inventory** (*Varasto*).
2. Navigate to **My Booth** (*Oma koju*).
3. Select the **first icon**.
4. Observe the resulting popup window.

## Expected Result

The edit popup should remain visible without being covered by the chat interface.

## Actual Result

The chat interface overlaps and partially obscures the edit popup.

## Issue Handling and Outcome

- **April 23, 2026:** I created the GitHub issue and documented the affected UI area, reproduction steps, expected behavior, and actual behavior.
- **April 23, 2026:** A developer commented that the issue had been fixed, referencing commit [`4d004d7`](https://github.com/Alt-Org/Altzone/commit/4d004d7).
- **April 23, 2026:** The issue was closed as **completed**.

**Verification note:** The public issue confirms a developer-reported fix and closure. It does **not** document a separate post-fix retest performed by me; no such verification is claimed here.

## Testing Skills Demonstrated

- Identifying a visible user-interface defect
- Writing reproducible navigation steps
- Distinguishing expected from actual behavior
- Reporting findings through GitHub Issues
- Supporting communication between testing and development

## Portfolio Context

This example is based on a real issue I reported while testing ALT Zone. The text has been organized in English for portfolio presentation; the original GitHub issue remains the primary record of the observation and its handling.
