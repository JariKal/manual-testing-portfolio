# Bug Report Example – Clan Language Selection Icons (#1309)

**Project:** ALT Zone (multiplayer mobile game)  
**Area:** User Interface – Stone Castle Profile / Clan Settings  
**Original report:** [Alt-Org/Altzone Issue #1309](https://github.com/Alt-Org/Altzone/issues/1309)  
**Reported by:** [JariKal](https://github.com/JariKal)  
**Reported:** February 13, 2026  
**Original priority:** Low  
**Issue status:** Closed as completed on May 15, 2026

## Reported Problem

The Swedish and Spanish language options did not have corresponding icons in the clan language selection interface.

## Steps to Reproduce

1. Open the Stone Castle profile (*Kivilinnan profiili*).
2. Open Clan Settings (*Klaanin asetukset*).
3. Select **Choose Clan Language** (*Valitse klaanin kieli*).
4. Observe the language option icons.

## Expected and Actual Behavior

**Actual behavior:** The Swedish and Spanish language options were missing icons, as documented in the original issue.

**Expected behavior (inferred from the reported defect):** Each displayed language option should have an appropriate icon, or unsupported options should not be shown. The original issue did not explicitly fill out its Expected Behavior field.

## Developer Discussion and Requirement Clarification

The issue prompted a discussion about which languages the game should support:

- One contributor noted that only Finnish and English should have been available at that time and that icons for both already existed.
- Another contributor explained that Swedish was expected to be supported later, and Spanish had been added as a fallback for a test clan configured on the server to avoid a crash.

This illustrates how a UI defect report can reveal a need to clarify expected behavior and requirements, rather than simply add missing assets.

## Outcome and Limits of Evidence

The issue was **closed as completed on May 15, 2026**. The visible issue discussion does **not** establish precisely which UI or code change was made, and it does **not** document a separate retest performed by me. Accordingly, this portfolio entry does not claim a confirmed implementation detail or personal retest.

## Skills Demonstrated

- Manual user interface testing
- Identifying and reporting missing UI elements
- Providing a short navigation path to reproduce an issue
- Communicating findings through GitHub Issues
- Supporting requirement clarification through defect reporting
- Following the issue's documented lifecycle

## Source and Attribution

This is an English-language portfolio adaptation of a real ALT Zone bug report filed by me. The developer discussion is summarized, not presented as my own work. For the original wording and timeline, see [Issue #1309](https://github.com/Alt-Org/Altzone/issues/1309).
