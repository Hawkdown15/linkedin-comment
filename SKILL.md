---
name: linkedin-comment
description: Find recent Navodaya-ecosystem posts on LinkedIn, read and understand each post deeply, write a specific, emotionally matched, positive, non-political comment for the Navodayans Talk page, show it with the post link for approval, and post only approved comments. Use when Raj says "/linkedin-comment", "LinkedIn comment", "NT comment" or "comment on Navodaya posts".
---

# Navodayans Talk — LinkedIn Comment Skill (v3.0)

## Who we are
Navodayans Talk (NT) is a media platform and podcast channel for Jawahar Navodaya Vidyalaya (JNV) alumni, a sub-brand of Nav Fusion Media (Founder: Raj Satyan). NT serves a community of 50,000+ Navodayans. We comment as the NT page, as a proud, warm member of the Navodayan family.

NT LinkedIn page: https://www.linkedin.com/in/navodayanstalk/

**The one rule above all:** never write a comment until you have fully read and understood the post. A comment that could sit under any other post is a failure.

## Arguments
- No argument → find up to 5 posts.
- A number (e.g. `/linkedin-comment 8`) → up to that many posts (max 10).
- A LinkedIn post URL → skip search and work on that one post.

---

## Step 1 — Open LinkedIn
- Use Claude in Chrome (Raj's own Chrome, signed in to LinkedIn).
- Open https://www.linkedin.com/in/navodayanstalk/. Confirm Raj is signed in with admin access to the page. If not, stop and ask him to sign in.
- Read `data/comment-log.csv` so you never comment twice on the same post.

## Step 2 — Find recent Navodaya-ecosystem posts
Look in this order until you have enough:
1. The NT page's **Notifications → Mentions**.
2. LinkedIn search → **Posts** → sort by **Latest** → **Past 24 hours** (widen to **Past week** if needed), keyword by keyword:
   `Navodaya`, `Navodayan`, `JNV`, `Jawahar Navodaya Vidyalaya`, `Navodaya alumni`, `JNVST`, `#Navodaya`, `#JNV`, `#Navodayan`
3. Browse at a human pace. Never use scrapers or APIs.

**Skip a post if:**
- It's in the comment log, or posted by Navodayans Talk itself.
- It is about politics, elections, parties, politicians, government policy debates, protests, court cases, exam leaks, complaints or grievances against NVS/JNV or anyone, religion, caste, reservation, or any controversy.
- It is about a death, accident or tragedy → don't comment; list it at the end as "Skipped — sensitive" with its link.
- Navodaya is only mentioned in passing.

---

## Step 3 — Read each post completely (no shortcuts)
- **Open every post on its own page** (its own post URL, in a new tab). Never judge a post from the search-result card or the feed preview — those cut the text.
- Click every "…see more" and scroll to the very end.
- Capture the **full text word for word**, in its original language (English, Hinglish or Hindi). Don't summarise yet.
- **Images:** look at each image. Read all text on it. Note what it shows: people, place, occasion, banners, certificates, trophies, uniforms, campus, the expressions on faces.
- **Carousels and documents:** go through every slide and page.
- **Video:** read the caption and subtitles if available. If you can't watch it, note "video not watched" and rely only on what you can read.
- **Reposts:** read the original post and the reposter's own note.
- **Author:** name, headline, JNV name and batch if visible, current role. Tagged people and who they are to the author (teacher, batchmate, parent, mentor).
- **Existing comments:** read the top 10 and note what's already been said.
- If any part can't be read, write that down. **Never guess or invent a detail.**

## Step 4 — Understand the post deeply (Post Understanding Card)
Work through every layer, in order, and write the card before drafting anything.

1. **Line-by-line read.** Go through the post sentence by sentence. For each sentence, note what it says and what it reveals about how the author feels.
2. **Weighted words.** List the exact words and phrases the author chose that carry weight: emotional words, numbers, years, "first", "finally", "after X years", names of teachers, friends, places, houses, JNV details, small-town or family references. Note why the author likely chose each one.
3. **Post type.** Achievement / career milestone / exam result / teacher tribute / nostalgia / reunion / event / giving back / mentoring / startup / sports or cultural win / student achievement / gratitude / announcement / reflection / other.
4. **Emotion map.**
   - Primary emotion (pride, gratitude, nostalgia, joy, relief, humility, determination, longing, love, respect, excitement, hope).
   - Secondary emotion.
   - Intensity, 1–5.
   - The emotion beneath the surface: the struggle behind the success, a parent's sacrifice, small-town roots, years of waiting, missing someone.
5. **Heart line.** The single line that carries the most feeling. Our comment must respond to this line.
6. **Author intent.** Why did they post this? What do they want readers to feel? What response would make them feel truly seen and understood?
7. **Navodaya thread.** Where Navodaya connects, stated or clearly implied. Pick the ONE thread truest to this post:
   - giving rural talent a fair start
   - teachers who became like parents
   - residential life that built independence and discipline
   - batchmates who became a lifelong family
   - migration that opened minds to another part of India
   - values carried from campus into careers
   - giving back to the next generation of Navodayans
   - the campus as home
   Never force a thread the post doesn't support.
8. **Comment gap.** What the existing comments already say (avoid it) and what nobody has said yet (our opportunity).
9. **Best angle.** One sentence: what our comment will do for this author.

## Step 5 — Write the comment

### Match the emotional temperature
| Post feeling | Our tone |
|---|---|
| Big joy, achievement | Warm, energetic celebration — honour the effort behind the result |
| Nostalgia, campus memories | Soft, warm, reflective — walk back into the memory with them |
| Teacher tribute, gratitude | Respectful, heartfelt, almost reverent |
| Humble milestone | Gentle respect, no over-hype |
| Struggle-to-success story | Honour the journey and the people who stood behind it, not just the result |
| Event, reunion, announcement | Excitement and warm good wishes |
| Giving back, mentoring | Deep appreciation for paying it forward |

### Structure (3–5 short blocks, flexible)
1. **Mirror the heart.** Open by responding to the heart line or the most specific detail. Show we truly read it. Don't open with a plain "Congratulations".
2. **Add meaning.** Say what this moment really represents — the unseen effort, the people behind it, why it matters.
3. **Navodaya gratitude.** Connect it, truthfully, to the role of Navodaya using the chosen thread.
4. **Community echo.** Speak for the Navodayan family: how every Navodayan feels reading this.
5. **Optional close.** A warm wish, or one light, easy question that invites the author and others to reply. Only when natural.

### Craft rules
- Echo 2–6 of the author's own words so they feel heard. Never copy whole sentences.
- Include one **memorable line**: a short, true, quotable line people will want to like.
- Use concrete details from the post (names, years, places, objects), not abstract praise.
- Vary openings within a run. Don't start two comments the same way.
- No stacked adjectives ("amazing, wonderful, incredible"). One precise word beats three loud ones.

### Fixed parameters (never change)
- **Always positive.** Appreciation, pride, celebration, gratitude. No criticism, sarcasm, complaints or "but".
- **Never political.** No parties, politicians, ideologies, government schemes, policy opinions, religion, caste, region or language debates. If an official appears in the post, appreciate the students, teachers, school or occasion — not the official.
- **Navodaya-oriented.** Every comment shows appreciation and gratitude for Navodaya.
- **On behalf of Navodayans Talk.** "We" = Team Navodayans Talk.
- **Format:** short line blocks, each separated by a blank line. 30–80 words.
- **Language:** match the post. English → English. Hinglish → Hinglish in Roman script. Hindi → Hindi in Devanagari.
- Use the author's first name when natural.
- 0–2 emojis. No hashtags. No links. No "follow us" or promotion.
- Posts about children/students: celebrate the achievement only; no personal details, no comments on appearance.

### Never use
"Great post", "Very inspiring", "Truly inspiring", "Keep it up", "Kudos", "Heartiest congratulations", "Many many congratulations", "So proud" on its own, "testament to", "delve", "tapestry", "resonates deeply", "embark", "in today's fast-paced world", or the word "journey" more than once.

### Draft, score, pick
1. Write **3 drafts**, each with a different angle.
2. Score each 1–5 on: Specificity · Emotional match · Navodaya gratitude · Memorable line · Invites likes/replies · Safety.
3. Safety must be 5. Every other score must be 4 or higher, or rewrite that draft.
4. Show Raj the highest-scoring draft. Keep the other two ready for `r`.

### Example — the quality bar

**Post (summary):** An alumnus visits his JNV after 18 years. The mess bell still rings at the same time. His retired teacher, Sharma sir, recognises him by his roll number before his name. He couldn't stop his tears. "Everything I am today started on that campus."

**Weak (never this):**
"Great memories! Navodaya is the best. Proud of you 👏"

**Strong (this level):**
"Recognised by roll number before name — after 18 years. 🥹

That one moment says everything about how Navodaya teachers carry their students: not as a batch, but as their own children.

Sharma sir didn't just remember you; he remembered who you were before the world knew you.

The mess bell, the campus, the tears — every Navodayan reading this just went back home for a minute.

Thank you for taking us along."

## Step 6 — Safety and quality check (every comment)
- [ ] Positive from first word to last
- [ ] Zero political, religious, caste or controversial content
- [ ] Responds to the heart line and uses at least one specific detail from the post
- [ ] Emotional tone matches the post
- [ ] Clear Navodaya appreciation and gratitude
- [ ] Contains one memorable line
- [ ] No banned phrases
- [ ] Short line blocks with blank lines, 30–80 words, language matches the post
- [ ] No invented details
If any check fails, rewrite and check again.

## Step 7 — Show for approval in the terminal
Show **one post at a time**, in exactly this format, with the comment inside double quotes:

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
POST 1 of 5
Link:    <full LinkedIn post URL>
Author:  <name> — <headline>
Posted:  <time ago>
About:   <one-line summary of the post>

Understanding:
  Emotion:          <primary> + <secondary> (intensity X/5)
  Heart line:       "<the line from the post>"
  Navodaya thread:  <chosen thread>
  Angle:            <best angle in one sentence>

Proposed comment:
"<block 1>

<block 2>

<block 3>"

Reply:  y = post   e = edit   r = rewrite   n = skip
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

Then **stop and wait for Raj's reply.** Never post without a "y" for that specific comment.
- `y` → Step 8.
- `e` → Raj types his edited text. Show it again in the same format inside double quotes and ask for `y`.
- `r` → show the next-best draft. Once both spare drafts are used, write a fresh one with a new angle.
- `n` → skip, log as `skipped`, next post.

## Step 8 — Post the approved comment
- Open the post link.
- Click **Comment**, then switch **"Commenting as"** to **Navodayans Talk**. Confirm the page identity is selected before typing.
- Paste the approved text exactly, keeping the blank lines between blocks.
- Check the comment box once more, then click **Post**.
- Confirm the comment is visible under the Navodayans Talk name.
- Print:
  ```
  ✅ Posted as Navodayans Talk
  Check it here: <full LinkedIn post URL>
  ```
- If anything fails, stop and print the comment in double quotes with the link so Raj can post it manually.
- Wait about 2 minutes before the next post.

## Step 9 — Log
Add a row to `data/comment-log.csv` for every post shown: date, post URL, author, one-line summary, final comment text, status (`posted`, `skipped`, or `failed`).

## Step 10 — Final summary
Print:
- Posted comments, each with its post link.
- Skipped posts, each with its link.
- "Skipped — sensitive" posts, each with its link, for Raj's manual review.

## Limits
- Maximum 10 posts per run and about 15 comments per day.
- Never like, follow, connect, message or repost anything. Only comment, and only after approval.

## Raj's extra rules
<!-- carried over from v2.0 -->
- **Browser:** use the Chrome with deviceId starting `3f3538c9` (navodayanstalk@gmail.com). Identify it by deviceId, because the "Browser N" names reshuffle. Open a new tab.
- **Identity:** Navodayans Talk is a LinkedIn **profile**, not a company page, so there is no admin role to check. Step 1 passes when the signed-in profile is Navodayans Talk. In Step 8 the "Commenting as" switch is the identity dropdown beside Like ("Comment, react, and repost as"). Pick **Navodayans Talk**, never "Navodayans Talk & Education".
- **No invented memories.** "We" speaks as the team. Never claim we were at the author's JNV or remember a specific event.
- **Extra skips:** posts older than 7 days; posts on a student's own profile when they are under 18; festival greetings and sales/partnership promotions; false matches and the other sensitive zones in `references/safety-rules.md` (Navodaya Institute of Technology Raichur, Navodaya Medical College, Navodaya Education Trust, JNV Group, JNV University Jodhpur and others).
- **Background:** read `references/` in Step 1 (ecosystem, audience, voice guide, comment patterns, safety rules).
- **Machine-tell check:** in Step 6, also run `/li-human` (`humanize.py FILE --report`, `detect.py FILE`) on the chosen draft. The bar is no FLAGGED verdict and no structural tells; PASS is out of reach on short comments. Note: `humanize.py` turns em dashes into commas.
- **Mentions:** open `linkedin.com/notifications/` and click the **Mentions** pill; the `?filter=mentions` URL does not switch tabs.
- **Search URL:** `linkedin.com/search/results/content/?keywords=<term>&datePosted=%22past-24h%22&sortBy=%22date_posted%22` (or `%22past-week%22`). Expect to widen to Past week. Bare `Navodaya` is mostly false matches.
- **Post links:** search cards don't expose URLs. Real-click the post's "…" menu (JavaScript clicks don't open it), click "Copy link to post", then read it with `pbpaste`. It overwrites Raj's clipboard. The `lnkd.in/p/…` link opens the post on its own page.
- **Browser quirks:** `find` refs go stale, so find and click in one step. JavaScript output containing URLs gets blocked, so read pages with `get_page_text`.
- **Logging:** write rows with Python's `csv` module, because comments contain line breaks and commas.
