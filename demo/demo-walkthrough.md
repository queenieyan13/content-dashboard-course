# Demo Walkthrough — "Mei Ling" (test run of Sessions 1 & 2)

A full test run of both runners with a fictional student. Use it as the **live demo in class**, or to show students what good (specific) answers look like.

The finished dashboard is [demo-dashboard.html](demo-dashboard.html).

---

## Session 1

**AI:** Before we begin, what's your name, and what should I call you?
**Student:** Tan Mei Ling, call me Mei.
> 🏠 *Dashboard created: "Mei's Content Dashboard", with empty sections.*

### Part 1 · Background

| Q | Mei's answer (summarised) |
|---|---|
| 1 | Kuala Lumpur. English and Chinese. Instagram (1,200 followers) and 小红书 (just started). |
| 2 | Independent financial coach for 3 years. Before that, 8 years in retail banking. |
| 3 | At 25 she had RM40,000 of credit card debt while working *at a bank*. Paying it off in 3 years changed how she sees money. |
| 4 | Friends say: "patient, practical, funny". Loves hiking and café-hopping. |
| 5 | Wants clients, not just views. 6-month goal: **5,000 Instagram followers and 10 coaching clients from content.** |

> **Follow-up the AI asked on Q5:** "What does 'grow my account' mean in numbers?" This turned a vague answer into a trackable goal.
> 🪪 *Added: About Me + 6-Month Goal (1,200 / 5,000 followers).*

### Part 2 · Career & Positioning

| Q | Mei's answer (summarised) |
|---|---|
| 1 | Young working women (25–35) who earn decently but have nothing left at month end. Ideal viewer: "Jess, 28, marketing exec, RM5k salary, RM12k credit card debt, too embarrassed to ask for help." |
| 2 | Method: split every salary into 3 jars on payday: **Save** (debt + emergency), **Grow** (invest), **Enjoy** (guilt-free spending). |
| 3 | In debt at 25 while working at a bank, ashamed to tell anyone. Built the 3-jar system for herself, then coached friends. |
| 4 | 120+ clients. Average client saves RM800 more per month within 3 months. Licensed financial planner. |
| 5 | Brand "Money with Mei". Sage green + cream. Tone: friendly big sister. **Refuses:** fear-selling, get-rich-quick, pushing products. |

**Positioning (chosen):**
> "I help young working women stop living paycheck to paycheck through **The 3-Jar Money Reset**, because I paid off RM40k of debt while working at a bank, so I know shame isn't the problem; the system is."

Method name options offered: *The 3-Jar Money Reset* ✅ · *Payday Split System* · *Save-Grow-Enjoy Method*

**Content pillars:** ① Debt-Free Basics · ② Grow Your Money · ③ Guilt-Free Spending
> 🎯🧱 *Added: My Positioning + Content Pillars.*

### Part 3 · Content Reference

| Q | Mei's answer (summarised) |
|---|---|
| 1 | Likes creators who explain money with a whiteboard, who show real numbers on screen, and who talk to camera like a friend. |
| 2 | A video where a creator showed her own bank statement. "Real, not preachy." |
| 3 | Talking head, plus carousels. |
| 4 | Raw and honest, warm, a bit funny. |
| 5 | Never: flexing luxury, fake urgency, "you're poor because you buy coffee". |

> 🎨💡 *Added: Style Guide + Idea Bank (10 ideas). Mei starred 3.*

---

## Session 2 · First script

**Idea chosen:** ⭐ "Why I was RM40k in debt while working at a bank" (Pillar: Debt-Free Basics)

```
🎣 HOOK (pick one)
H1: Earning RM5k but broke by the 20th? Same. Here's why.
H2: Your salary isn't the problem. Your payday is.
H3: I worked at a bank and still owed RM40,000.

🧠 BODY
At 25, I was helping customers with their loans…
while hiding my own RM40k credit card bill.
[On-screen text: RM40,000 debt · age 25]
The problem wasn't how much I earned.
It was that my salary had no job.
So I gave it three.
[On-screen text: JAR 1 · SAVE]
First jar: Save. Debt and emergency money, paid first.
[On-screen text: JAR 2 · GROW]
Second jar: Grow. Even RM100 into investing.
[On-screen text: JAR 3 · ENJOY]
Third jar: Enjoy. Yes, guilt-free bubble tea.
I split it the day my salary comes in, before I can touch it.
Three years later, debt gone.
My clients save about RM800 more a month doing this.

🎯 SUMMARY + CTA
Give your salary three jobs on payday: save, grow, enjoy.
Comment "JAR" and I'll send you my 3-jar template.

📝 CAPTION
Worked at a bank. Still had RM40k debt. 🙃
The fix wasn't earning more. Comment "JAR" for my template.
```

**Hook chosen:** H3 (story). **One "doesn't sound like me" fix:** "Allocate your income strategically" → "split it the day my salary comes in."

---

## Issues found during the test (now fixed in the runners)

| # | Problem | Fix applied |
|---|---|---|
| 1 | Homework says "star 3 ideas", but the Idea Bank had no star button. | Session 1 prompt now asks for a ⭐ button. |
| 2 | A "Write script" button inside the dashboard **can't talk to the chat**. | The button now copies a ready-made prompt for the student to paste into the chat. |
| 3 | Scripts written in chat had no clear way into the dashboard. | Added "Save this script to my Script Studio" prompt + a paste-in form as backup. |
| 4 | Risk: when the AI updates the dashboard, it could **wipe data the student typed in**. | Dashboard rule added: keep typed-in data separate from built-in data and never overwrite it. |
| 5 | Tracker couldn't know the hook type of a post. | Each planner post now carries its pillar and chosen hook (H1/H2/H3). |
