# BuyGoods (BG) Compliance Changes - v2

Tracking all compliance modifications made for BuyGoods approval.
Use this document to reverse changes once approved / when ready to restore original content.

---

## Change Types

### Type A - Direct Content Modifications
Changes made directly to the content for compliance. No backup stored — original wording is documented here for manual restoration.

### Type B - Temporary Modifications (Backup Stored)
Original files/sections backed up before modification. Restore by replacing the modified version with the backup.

---

## Type A - Direct Content Modifications

| # | File | What Changed | Original Content | Compliant Content | Status |
|---|------|-------------|-----------------|-------------------|--------|
| 1 | short/go/index.html | Subscription text in FAQ (Line ~2205) | "We offer both one-time purchase and subscription options. With a one-time purchase, you pay once with no automatic recurring charges. If you choose a subscription, you'll enjoy savings on each order and can cancel anytime with no hassle." | "We offer a one-time purchase option. You pay once with no automatic recurring charges." | Active |
| 2 | long4/go/index.html | All IG/Irvingia Gabonensis/African Mango name references replaced with generic text ("this extract", "this tropical seed", etc.) | Various — "Irvingia Gabonensis, or IG", "African Mango seed", "IG" throughout | Generic references: "this novel seed extract", "this tropical seed", "this extract", "the core ingredient" | Active |
| 3 | long4/go/index.html | All ingredient cards removed (Niacin, Rhodiola, Astragalus, L-Ornithine, L-Carnitine, L-Arginine, L-Glutamine, Maca, Beta-Alanine) — not in supplement | Full card HTML blocks | Cards deleted, HTML comment marker left | Active |
| 4 | long4/go/index.html | Pricing table rows removed for non-label ingredients (10 rows), total updated $232.69 → $27.95 | Individual ingredient rows with prices | Only Pygeum Africanum row remains | Active |
| 5 | long4/go/index.html | "Like IG, Maca and the herb Rhodiola from Scandinavia while making sure they're all high quality" → generic | Original sourcing text with specific ingredients | "Making sure all the ingredients are high quality" | Active |
| 6 | long4/go/index.html | Notification popup default image updated | `../../popup/img/img/1bottle.png` | `../../lib/img/1_bottle_qb.png` | Active |
| 7 | long4/go/index.html | Guarantee period "180 days" → "60 days" in text + all badge alt text | "180 days after" / "180 Days Guarantee" | "60 days after" / "60 Days Guarantee" | Active |
| 8 | best/go/go.html | Removed Chromium Picolinate from 3 locations | "Chromium Picolinate and Magnesium BHB" / "Chromium Picolinate" | "Magnesium BHB" only | Active |
| 9 | best/go/go.html | Removed black pepper/BioPerine card + heading reference | "plus a healthy dose of black pepper..." / "And BioPerine®" card | Removed | Active |
| 10 | best/go/go.html | Updated pricing: $89→$79 (retail), $59→$64 (3-bottle), $39→$49 (6-bottle) across all mentions | Various old prices | Prices matching checkout | Active |
| 11 | best/go/go.html | Ingredient images: Irish Sea Moss/Bladderwrack/Burdock → Calcium BHB/Magnesium BHB/Sodium BHB with correct images | Seaweed ingredient images | BHB ingredient images from lib/img/ | Active |
| 12 | best/go/go.html | "four key fat busting ingredients" → "three" (after BioPerine removal) | "four" | "three" | Active |
| 13 | popup/js/social-proof.js | Updated customerProducts array with correct QB bottle images and varied quantities (1,2,3,6,7) | `single_bottle.webp` (1-bottle only, 3 entries) | `lib/img/1_bottle_qb.png`, `2-bottles-qb.webp`, `3-bottles-qb.webp`, `6-bottles-qb.webp`, `7-bottles-qb.webp` (9 entries with weighted distribution) | Active |
| 14 | ALL pages (22 files) | Notification popup default images updated to correct QuickBurn BHB bottle image | `popup/img/img/1bottle.png` or `popup/img/single_bottle.webp` (various relative paths) | `lib/img/1_bottle_qb.png` (various relative paths) | Active |
| 15 | short/go/t.html, t-2.html, r.html, r-2.html, o.html, e.html | Product name in notification fixed | "Meta Trim BHB" | "QuickBurn BHB" | Active |
| 16 | index_disabled.html | Product name in notification fixed | "Metatrim BHB" | "QuickBurn BHB" | Active |
| 17 | popup/index.html | Product name in notification template fixed | "MetaTrim BHB" | "QuickBurn BHB" | Active |

---

## Type B - Temporary Modifications (Commented Out in HTML)

Original content preserved inside HTML comments with `BG-COMPLIANCE:` markers. To restore, remove the comment tags.

| # | File | What Was Commented Out | Comment Marker | Status |
|---|------|-----------------------|----------------|--------|
| 1 | short/go/index.html | Irish Sea Moss ingredient card (Line ~1219) | `BG-COMPLIANCE: Irish Sea Moss ingredient card removed (not on label)` | Active |
| 2 | short/go/index.html | Entire "Supporting Ingredients" section — Green Tea Extract, Apple Cider Vinegar, MCT Oil Powder (Line ~1246) | `BG-COMPLIANCE: Entire Supporting Ingredients section removed` | Active |
| 3 | short/go/index.html | Irish Sea Moss, Green Tea Extract, Apple Cider Vinegar lines in FAQ "What's inside" section (Line ~2195) | `BG-COMPLIANCE: Irish Sea Moss, Green Tea Extract, Apple Cider Vinegar removed from FAQ (not on label)` | Active |
| 4 | short/go/index.html | Subscription text in FAQ "Purchasing options" (Line ~2205) | `BG-COMPLIANCE: Subscription text removed (no subscription options available)` | Active |
| 5 | upsell3.html | Hero: removed "FREE! FREE! FREE!", "Just Pay Minor Shipping Charges", "FREE Trial Offer" | `BG-COMPLIANCE: Removed FREE mentions` | Active |
| 6 | upsell3.html | Offer header: "Risk-Free" removed | `BG-COMPLIANCE: Removed "Risk-Free"` | Active |
| 7 | upsell3.html | Pricing: $0/bottle + $19.99 shipping → $19.99/bottle + Free Shipping. Subscription: added "First month just $19.99", changed "$69+Shipping" to "$69" | `BG-COMPLIANCE: Changed $0/bottle + $19.99 shipping → $19.99/bottle + Free Shipping` | Active |
| 8 | upsell3.html | Bottom CTA: "$19.99 shipping" → "$19.99 with Free Shipping" | `BG-COMPLIANCE: Removed "$19.99 shipping" wording` | Active |
| 9 | long2/index.html | "Miraculous" → "Remarkable" in main heading | `BG-COMPLIANCE: "Miraculous" → "Remarkable"` | Active |
| 10 | long2/index.html | "killing yourself" → "hurting yourself" | `BG-COMPLIANCE: "killing yourself" → "hurting yourself"` | Active |
| 11 | long2/index.html | Removed John Rowley + Fox News/media outlets line | `BG-COMPLIANCE: Removed John Rowley + media outlets line` | Active |
| 12 | long2/index.html | Removed drug abuse study claim (Gerber et al) | `BG-COMPLIANCE: Removed unverified drug abuse study claim` | Active |
| 13 | long2/index.html | Removed "weak. Fat. Sore all over" line | `BG-COMPLIANCE: Removed "weak. Fat. Sore all over" line` | Active |
| 14 | long2/index.html | Removed John Rowley signature + jrsig2.png | `BG-COMPLIANCE: Removed John Rowley signature` | Active |
| 15 | long2/index.html | "reversing" → "reducing" (health problems) | `BG-COMPLIANCE: "reversing" → "reducing"` | Active |
| 16 | long2/index.html | "VANISHING" / "vanishing" → "reducing" (2 instances) | `BG-COMPLIANCE: "vanishing" → "reducing"` | Active |
| 17 | long2/index.html | "miraculous power of Lipase-P" → "remarkable power of this thinning enzyme" | `BG-COMPLIANCE: "miraculous" → "remarkable", removed Lipase-P` | Active |
| 18 | long2/index.html | ALL Lipase-P mentions replaced with "thinning enzyme" / "enzyme levels" / "this enzyme" (~30+ instances) | `BG-COMPLIANCE: Removed ALL Lipase-P mentions` | Active |
| 19 | long2/index.html | Price: "$19" → "$49/bottle" (3 instances) | `BG-COMPLIANCE: Updated $19 price to $49` | Active |
| 20 | long2/index.html | Guarantee heading: "Guarantee You'll Lose The Weight" → "Money-Back Promise", guarantees reworded to satisfaction-based | `BG-COMPLIANCE: Reworded guarantees to satisfaction-based` | Active |
| 21 | long2/index.html | "dangerous drugs/medications" → "strong drugs/medications" (3 instances) | `BG-COMPLIANCE: Removed "dangerous"` | Active |
| 22 | long2/index.html | Scare section removed: "nursing home...deteriorate...never having lived it at all" → positive framing | `BG-COMPLIANCE: Removed scare section` | Active |
| 23 | long2/index.html | "GUARANTEED" claim removed from body text | `BG-COMPLIANCE: Removed "GUARANTEED" claim` | Active |
| 24 | long4/go/index.html | Intimate couple image (RVS-26.webp/png) removed (Line ~2578) | `BG-COMPLIANCE: Intimate couple image removed` | Active |
| 25 | long3/page5.html | "incredibly dangerous" → "holding you back" (2 instances, Lines ~2460, ~2469) | `BG-COMPLIANCE: "incredibly dangerous" → "holding you back"` | Active |
| 26 | long4/go/index.html | "restore" → "support" (multiple instances) | `BG-COMPLIANCE: "restore" → "support"` | Active |
| 27 | long4/go/index.html | Removed "already helped over 400,000 men and women" claim (desktop + mobile) | `BG-COMPLIANCE: Removed "400,000" claim (unverified)` | Active |
| 28 | long4/go/index.html | "treatment group" → "regimen group" (body text + 2 headings desktop/mobile). Also removed "IG" from headings | `BG-COMPLIANCE: "treatment group" → "regimen group"` | Active |
| 29 | long4/go/index.html | "dangerous toxins" → "harmful toxins" | `BG-COMPLIANCE: "dangerous toxins" → "harmful toxins"` | Active |
| 30 | best/go/go.html | "miracle vegetable" → "remarkable vegetable" (3 instances) | `BG-COMPLIANCE: "miracle vegetable" → "remarkable vegetable"` | Active |
| 31 | best/go/go.html | "Miracle Health supplement" → "Remarkable Health supplement" | `BG-COMPLIANCE: "Miracle" → "Remarkable"` | Active |
| 32 | best/go/go.html | Removed "Over 200,000 people have gotten dramatic results" claim | `BG-COMPLIANCE: Removed "200,000 people" claim (unverified)` | Active |
| 33 | best/go/go.html | "Preventing fat absorption" → "Supporting healthy fat metabolism" (2 instances) | `BG-COMPLIANCE: "Preventing" → "Supporting healthy"` | Active |
| 34 | best/go/go.html | "protect this seaweed" → "preserve this seaweed" | `BG-COMPLIANCE: "protect" → "preserve"` | Active |
| 35 | best/go/go.html | "Protects vision" → "Supports vision" | `BG-COMPLIANCE: "Protects" → "Supports"` | Active |
| 36 | best/go/go.html | "prevent fat storage" → "support healthy fat metabolism" | `BG-COMPLIANCE: "prevent fat storage" → "support healthy fat metabolism"` | Active |
| 37 | best/go/go.html | "protected for up to six months" → "supported for up to six months" | `BG-COMPLIANCE: "protected" → "supported"` | Active |
| 38 | best/go/go.html | "investment is protected by" → "investment is backed by" | `BG-COMPLIANCE: "protected" → "backed"` | Active |
| 39 | best/go/go.html | "Fully Protected by Our" → "Fully Covered by Our" | `BG-COMPLIANCE: "Protected" → "Covered"` | Active |
| 40 | best/go/go.html | "It has prevented you from living" → "It has held you back from living" | `BG-COMPLIANCE: "prevented" → "held you back from"` | Active |
| 41 | best/go/go.html | "war in Ukraine, and out-of-control inflation" → "global supply-chain disruptions and rising costs" | `BG-COMPLIANCE: Removed "war in Ukraine" reference` | Active |
| 42 | best/go/go.html | "results in as early as one week" → "a few weeks" (3 instances) | `BG-COMPLIANCE: "one week" → "a few weeks"` | Active |
| 43 | best/go/go.html | "after taking it for 30 days" → "after taking it for a few weeks" | `BG-COMPLIANCE: "30 days" → "a few weeks"` | Active |

---

## Restoration Instructions

### To reverse Type A changes:
1. Find the entry in the table above
2. Locate the file and line/section described
3. Replace the "Compliant Content" with the "Original Content"
4. Update the Status column to "Restored"

### To reverse Type B changes:
1. Find the entry in the table above
2. Copy the backup file from the "Backup Location" path
3. Replace the modified file with the backup
4. Verify the restoration is correct
5. Update the Status column to "Restored"

---

## Status Legend
- **Active** — Compliance change is currently live
- **Restored** — Original content has been put back
- **Deprecated** — Change is no longer relevant

---

*Created: February 18, 2026*
*Last updated: February 19, 2026*
