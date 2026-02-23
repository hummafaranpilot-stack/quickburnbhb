# BuyGoods Compliance - Reversal Log

Changes made for BG compliance that should be reversed after final approval.

---

## v2/long2/index.html

### 1. "miracle enzyme" (Line ~1056)
- **Original:** `"...elevating this miracle enzyme naturally?"`
- **Changed to:** `"...elevating this remarkable enzyme naturally?"`
- **Reversal:** Uncomment the original line and remove the replacement.

### 2. "My personal miracle" heading (Line ~1184)
- **Original:** `"My personal miracle was delivered in a magazine..."`
- **Changed to:** `"My path to better health started with a magazine..."`
- **Reversal:** Uncomment the original line and remove the replacement.

### 3. "Why QuickBurn BHB Works" — Lipase-P mechanism section (Line ~1686-1690)
- **Original:** Entire section claiming the supplement works via pancreatic Lipase-P enzymes ("plain-old lipase", "boost levels inside your pancreas", "thinning enzyme effect")
- **Changed to:** Rewritten to pitch supplement + diet combination approach without Lipase-P claims
- **Reversal:** Uncomment the original block and remove the replacement paragraphs.

### 4. Pancreatic lipase study reference (Line ~1697)
- **Original:** `"Dr. Richard G. Fessler revealed Pancreatic lipase may be beneficial in treating autoimmune disorders such as rheumatoid arthritis and some food allergies."`
- **Changed to:** `"Dr. Richard G. Fessler suggests that supporting healthy fat metabolism may also benefit joint comfort and overall immune balance."`
- **Reversal:** Uncomment the original line and remove the replacement.

### 5. "Fat Vanishes" publication nickname (Line ~1030)
- **Original:** `"The Land Where Fat Vanishes."`
- **Changed to:** `"The Land Where Fat Fades Away."`
- **Reversal:** Uncomment the original line and remove the replacement.

### 6. "vanished" in testimonial (Line ~1418)
- **Original:** `"My shortness of breath, knee and back issues have all vanished."`
- **Changed to:** `"My shortness of breath, knee and back issues have all improved significantly."`
- **Reversal:** Uncomment the original line and remove the replacement.

---

## v2/long3/page4.html

### 7. Removed fgr3.jpg image (Line ~309)
- **Original:** `<img src="img/fgr3.jpg" class="button mt-4">`
- **Changed to:** Commented out
- **Reversal:** Uncomment the image tag.

---

## v2/best/go/go.html

### 8. Removed Irish Sea Moss & Bladderwrack sections — unmatched ingredients (Lines ~1910-2106)
- **Original:** Full "Irish Sea Moss" section (Calcium BHB card with colin-20, colin-21, colin-22a-f images, health benefit claims), full "Bladderwrack" section (Magnesium BHB card with colin-23, colin-24a-c images, health benefit claims), and combined conclusion line ("Irish Sea Moss and Bladderwrack were the two best seaweeds")
- **Changed to:** Entire block wrapped in `<div style="display:none" class="bg-compliance-hidden-seaweed">`. Replaced with 2 paragraphs referencing actual BHB salt ingredients (Calcium BHB, Magnesium BHB, Sodium BHB).
- **Reversal:** Remove the `<div style="display:none" class="bg-compliance-hidden-seaweed">` wrapper and its closing `</div>`, then remove the 2 replacement paragraphs.

---
