# ⚙️ IMPLEMENTATION WORKFLOW — From Product to Published Ad

> **Follow this step-by-step process every time you create a new UGC campaign.**

---

## OVERVIEW

```
PHASE 1: INPUT → PHASE 2: GENERATE → PHASE 3: ADAPT → PHASE 4: PRODUCE → PHASE 5: TEST
```

Estimated time per campaign: **90–120 minutes** (first time) | **30–45 minutes** (repeat)

---

## PHASE 1: PRODUCT INPUT (10 min)

**Goal:** Gather all the information AI needs to generate great output.

1. Open [`templates/product_input_template.md`](../templates/product_input_template.md)
2. Fill in every field — don't skip any
3. Save your completed input as `[product-name]_input.md`

**Checklist:**
- [ ] Product name and category filled
- [ ] 3 key benefits defined (specific, not vague)
- [ ] Target audience described with at least 1 persona detail
- [ ] Pain point stated as the customer would say it (not marketing speak)
- [ ] Offer/CTA confirmed and currently live
- [ ] Platform priority selected

---

## PHASE 2: AI GENERATION (20–30 min)

Run these prompts in order, feeding each output into the next prompt as input.

**Step 1 — Master Script** (10 min)  
→ Use [`prompts/01_master_prompt.md`](../prompts/01_master_prompt.md)  
→ Paste your product input, run the prompt  
→ Save the output

**Step 2 — Hook Expansion** (5 min)  
→ Use [`prompts/02_hook_generator.md`](../prompts/02_hook_generator.md)  
→ Take the 5 hooks from Step 1, ask AI to generate 5 more using different formulas  
→ You now have 10+ hooks

**Step 3 — Psychology Layer** (5 min)  
→ Use [`prompts/07_conversion_psychology.md`](../prompts/07_conversion_psychology.md)  
→ Paste your best script into this prompt  
→ Get the psychologically-enhanced version

**Step 4 — Brand Voice** (5 min)  
→ Use [`prompts/05_brand_voice_customization.md`](../prompts/05_brand_voice_customization.md)  
→ Apply your brand voice to the enhanced script

**Step 5 — Complete Pack** (5 min)  
→ Use [`prompts/08_complete_content_pack.md`](../prompts/08_complete_content_pack.md)  
→ Generate captions, hashtags, B-roll list, CTA variations

---

## PHASE 3: ADAPTATION (10 min)

**Goal:** Create platform-specific versions.

1. Use [`prompts/04_platform_adaptation.md`](../prompts/04_platform_adaptation.md)
2. Adapt the final script for your top 2 platforms (start with primary)
3. Note any platform-specific changes needed (CTA format, caption length, audio)

**Output per platform:**
- [ ] Adapted script (with [VISUAL] / [VOICEOVER] / [TEXT OVERLAY] labels)
- [ ] Platform-specific caption
- [ ] Hashtag set
- [ ] CTA variation

---

## PHASE 4: PRODUCTION (30–60 min)

**Goal:** Shoot and edit the video.

**Pre-Production Checklist:**
- [ ] B-roll shot list prepared (from content pack)
- [ ] Location/setup ready
- [ ] Creator/talent briefed
- [ ] Props / product ready for close-ups
- [ ] Lighting check (natural light or ring light)

**Shooting Order:**
1. Record hook in 3–5 takes (this is the most important shot)
2. Record the full script straight through (3–5 takes)
3. Capture all B-roll shots on the shot list
4. Get close-ups of product packaging, key features, and "hero moment"

**Editing Checklist:**
- [ ] Captions/subtitles added (auto-generated tools: CapCut, Submagic)
- [ ] Text overlays added at correct timestamps
- [ ] Music/sound selected (royalty-free or trending audio)
- [ ] First frame thumbnail-worthy
- [ ] Exported in 9:16, full HD (1080x1920)
- [ ] Video under platform time limit
- [ ] No watermarks from other apps

---

## PHASE 5: LAUNCH & TEST (Ongoing)

**Goal:** Publish, measure, iterate.

**Publishing Checklist:**
- [ ] Caption finalized and pasted
- [ ] Hashtags added
- [ ] Link in bio updated (if applicable)
- [ ] Post at peak time for your audience (check platform analytics)

**A/B Test Setup:**
- [ ] Hook test variants ready (minimum 3)
- [ ] Metrics defined (see [`workflows/testing_framework.md`](testing_framework.md))
- [ ] Campaign brief updated ([`templates/campaign_brief_template.md`](../templates/campaign_brief_template.md))

**Monitoring Schedule:**
- **24 hours post-publish:** Check hook performance (thumb stop, 3-second views)
- **72 hours post-publish:** Check engagement (saves, shares, comments)
- **7 days post-publish:** Check conversion metrics (CTR, link clicks, sales)
- **14 days post-publish:** Final performance review, update tracking sheet

---

## ITERATION LOOP

```
Publish → Measure → Identify Weakest Element → Run Targeted Prompt → Improve → Republish
```

*Every iteration makes your next ad faster and better-performing.*
