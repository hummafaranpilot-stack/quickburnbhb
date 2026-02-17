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
*Last updated: February 18, 2026*
