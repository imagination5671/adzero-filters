# Filter data licenses and attribution

Last verified: 2026-07-16

This repository distributes filter **data**, not the AdZero application or extension source code. The notices below apply only to the identified data files.

## EasyList-family derivative data

Files:

- `blocker_ads.json` — derived from EasyList
- `blocker_privacy.json` — derived from EasyPrivacy, plus AdZero-authored compatibility rules
- `blocker_annoyance.json` — derived from Fanboy's Annoyance List

Source and attribution: **The EasyList authors**, <https://easylist.to/>

Upstream license notice: <https://easylist.to/pages/licence.html>

EasyList makes this material available under a dual license. For the files listed above, AdZero selects **Creative Commons Attribution-ShareAlike 3.0 Unported, or any later version**:

- CC BY-SA 3.0: <https://creativecommons.org/licenses/by-sa/3.0/>
- EasyList repository: <https://github.com/easylist/easylist>

Changes made by AdZero: adaptation to Safari Content Blocker JSON, category packaging, structural validation, stable deduplication, rule-limit enforcement, and compatibility supplements. AdZero licenses its original contributions contained in these three data files under the same CC BY-SA 3.0-or-later terms.

## YousList derivative data

File: `blocker_korean.json`

Source and attribution: **YousList by yous and contributors**, <https://github.com/yous/YousList>

License: **Creative Commons Attribution 4.0 International**, <https://creativecommons.org/licenses/by/4.0/>

Changes made by AdZero: import from YousList's public `Rules.1blockpkg.json`, structural validation, stable deduplication, rule-limit enforcement, and addition of 16 AdZero-authored Hitomi compatibility rules. AdZero licenses those 16 original rules under CC BY 4.0 for distribution as part of this file.

## AdZero-authored filter data

Files:

- `blocker_custom.json`
- `blocker_privacy_extra.json`

Copyright © 2026 AdZero. These two data files are licensed under **CC BY 4.0**, <https://creativecommons.org/licenses/by/4.0/>.

## No application-code license grant

Nothing in this document grants a license to the AdZero iOS/iPadOS application, Safari extensions, user interface, trademarks, or other executable source code. This notice exists to satisfy the attribution and redistribution terms of the separately licensed public filter data.
