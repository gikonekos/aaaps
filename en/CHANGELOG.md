# CHANGELOG

> **This repository is maintained primarily in Japanese.**
> The Japanese document ([CHANGELOG.md](../CHANGELOG.md)) is the authoritative text. This English document is a reference translation provided for international readers and may not always be fully up to date with the Japanese original.

A human-readable revision history, summarizing "what changed" separately from the Git commit history.

## Translation addition (after the v1.0 release)
- Added `en/GOVERNANCE.md`, `en/CHANGELOG.md`, `en/CREDITS.md`, and `en/evidence.md`.
- Added `en/HISTORY.md` as a summary rather than a full translation, noting at the top that the Japanese version is authoritative and should be consulted for full detail.
- Updated the file tables in README.md / en/README.md with links to each English document.
- No changes were made to the content of the v1.0 release itself (AAAPS-v1.md, etc.).

## draft0.1
- Initial version. A single-file draft of the terms (based on a Gemini draft).

## draft0.2
- Split into README / AAAPS-v1 (main body) / GOVERNANCE / HISTORY / CREDITS / evidence.
- Narrowed the scope of the rights claimed to creative works specific to "Gikoneko" (Article 2).
- Softened Article 3 from "prohibits" to "does not consent to and objects to / is intended to serve as supporting material."
- Changed the copyleft carry-forward in Article 5 to mandatory ("MUST").
- Article 6 stated that CC BY-SA 4.0 was adopted as the base license.
- Added the 2002 Takara incident to HISTORY.md. Clarified the origin of the name "AAAP" (in tribute to a now-dissolved NPO).
- Stored the Facebook icon image under `assets/`.

## draft0.3
- Reverted Article 5 to "strongly recommended (SHOULD)," and explicitly listed MUST vs. SHOULD as an open issue.
- Revised Article 6 to the more cautious wording "references CC BY-SA, etc.," leaving the legal relationship as an open issue.
- Added an "Open Issues" section to GOVERNANCE.md (listing Articles 5 and 6).
- Added an opening statement to HISTORY.md: preserving and publishing both favorable and unfavorable records.
- Revised "serve as proof" to "intended to serve as supporting material" / "final evaluation is left to experts and third parties."
- Created `evidence/wikimedia.md` and `evidence/facebook.md`, adding fact-only timelines of public records on Wikimedia Commons / Japanese Wikipedia (2006, 2013, 2015) and confirmation that the Facebook page is viewable while logged out.
- Stored the corresponding screenshots under `evidence/wikimedia/` and `evidence/facebook/`, named using ISO 8601 dates.
- Created this CHANGELOG.md.

## draft0.4
- Added a "Basic Understanding of Authorship" section to HISTORY.md, stating the policy of treating AA/character works as a chain of specific individual creators rather than as having "spontaneously emerged."
- Accordingly, documented the origin of Gikoneko (the fixed-handle poster "Neko" → "Kottouya" → the residents who named it), and noted that the source (the Wikipedia "Gikoneko" article) is flagged as needing verification, and that its first appearance traces to MOTOI Kenkichi's own user page (oldid=10442031, February 5, 2007) — i.e., a primary first-person account.
- Added Article 7 (Reference Use and Use of the Project Names by Others) to AAAPS-v1.md. Other communities may reference the structure of this specification; however, a modified version that guts the anti-monopoly purpose is not treated as the "Official Specification" — framed as a definition (what counts as official) rather than a declaration of invalidity. Due to the renumbering, the former Article 7 (disclaimer) became Article 8.
- Stopped using consecutive dots in distribution filenames (e.g. `draft0.3.zip`) in favor of hyphens (e.g. `draft0-4.zip`), to address cases (e.g. on iPad) where the extension was not recognized correctly.

## draft0.5
- Created `en/README.md` and `en/AAAPS-v1.md`. Added links to them from README.md.
- Stated at the top of the English documents that the Japanese version is authoritative and the English version is a reference translation. GOVERNANCE / HISTORY / CREDITS / CHANGELOG / evidence remained Japanese-only for the time being, to be translated later as needed.

## draft0.6
- Created `LICENSE.md`, an entry-point file for GitHub's license detection, whose content is limited to pointing to `AAAPS-v1.md` as the authoritative text.
- Added a two-line "The role of AI review" section to GOVERNANCE.md (review from multiple generative AI systems was used, but final decisions are made by the editor).
- Added LICENSE.md to the file table in README.md.

## v1.0
First public release.
- Following ChatGPT's final review, incorporated minor additions: mentioned "canonical documents" once in en/README.md, and added "This file exists for repository tooling compatibility." to LICENSE.md.

---
Last updated: 2026-07-07
