# IntuBlade Outbound: Rep Setup Guide

Get set up in 15 minutes. No coding. No terminal. No tech skills needed.

You're going to use Claude (an AI assistant from Anthropic) to write personalized
cold emails to fire and EMS departments. Claude knows IntuBlade's product, our
sales playbook, and six expert sales advisors who score every email before you
send it. It also has a built-in filter that catches AI-sounding language and
rewrites it so your emails sound like a real person wrote them.

Your job: do the research (Google the department, find recent news, find the
chief and medical director), paste what you find into Claude, and let it write
the email in your voice. You review, edit if needed, and send from Gmail.

---

## Step 1: Get a Claude Pro account (2 min)

1. Go to **claude.ai**
2. Click "Sign up" (or sign in if you already have an account)
3. Upgrade to **Pro** ($20/month). Click your name in the bottom-left corner,
   then "Upgrade to Pro." You need Pro for the Projects feature.

If you already have a Pro or Max account, skip this step.

---

## Step 2: Create your IntuBlade Outbound project (5 min)

Projects let you give Claude a set of files it reads every time you start a
conversation. This is how Claude knows the IntuBlade playbook, the council
rubric, and your voice.

1. On claude.ai, click **"Projects"** in the left sidebar
2. Click **"Create project"**
3. Name it: **IntuBlade Outbound**
4. For the description, type: "Cold outreach for IntuBlade video laryngoscopes"
5. Click **"Create"**

Now you need to add the knowledge files. Andrew will send you a zip file (or a
Google Drive link) with these files. Upload them one at a time:

### Files to upload as Project Knowledge:

Click **"Add content"** then **"Upload files"** for each of these:

**Required (upload all of these):**

| File | What it does |
|------|-------------|
| `CLAUDE.md` | Master instructions. Tells Claude what IntuBlade is, how to write emails, quality gates. |
| `anti-ai-slop.md` | Banned words and phrases. Stops Claude from writing "I hope this finds you well" and other AI garbage. |
| `your-voice.md` | YOUR voice profile. You'll create this in Step 3. |

**Council advisor references (upload all 6):**

| File | Advisor |
|------|---------|
| `schwartz.md` | Eugene Schwartz. Copywriting, awareness levels, headlines. |
| `hormozi.md` | Alex Hormozi. Offers, pricing, making the deal irresistible. |
| `klaff.md` | Oren Klaff. Frame control, authority, not sounding like a sales rep. |
| `cialdini.md` | Robert Cialdini. Persuasion psychology, social proof, specificity. |
| `voss.md` | Chris Voss. Tactical empathy, questions that invite replies. |
| `rackham.md` | Neil Rackham. SPIN selling, opening conversations not closing them. |

**IntuBlade-specific references (upload all 3):**

| File | What it covers |
|------|---------------|
| `physician-founder-frame.md` | How Andrew's EM doc + Army medic background changes the sale |
| `public-safety-buyer.md` | How fire/EMS chiefs actually buy, budget cycles, grant signals |
| `deployment-kit-psychology.md` | The free deployment kit offer, dollar anchoring, tier structure |

That's 13 files total. Once uploaded, they show up under "Project Knowledge"
in your project. Claude reads all of them every time you start a new conversation
in this project.

---

## Step 3: Create your voice profile (5 min)

Andrew sent you a file called `voice-template.md`. Open it in any text editor
(TextEdit on Mac, Notepad on Windows, or Google Docs).

Fill it out honestly. This is how Claude learns to write like you, not like a
generic AI. Key sections:

- **Your tone** — are you casual? Direct? Warm? Pick what fits.
- **Your opener style** — write an example first sentence you'd actually send.
- **Your closer** — how do you sign off? "Talk soon"? Just your name?
- **Words you actually use** — phrases that are genuinely yours.
- **Words you NEVER say** — anything that sounds wrong coming from you.

Save it as `your-name.md` (e.g., `danny.md`) and upload it to your project
as Project Knowledge (same way you uploaded the other files).

---

## You're set up. Here's how to use it.

### Starting a new conversation

1. Go to your **IntuBlade Outbound** project on claude.ai
2. Click **"New conversation"** (or the pencil icon)
3. You're now talking to Claude with all the IntuBlade knowledge loaded

### The workflow for each department

**You do the research. Claude writes the email.**

Here's the process for one department:

#### 1. Research the department (5-10 min, you do this)

Google the department. You're looking for:

- **The chief's name and email.** Check the department website or city staff
  directory. Not LinkedIn guesses.
- **The medical director.** Check hospital system EMS pages, or Google
  "[department name] medical director."
- **A recent signal.** Something current: a grant they received, a new chief
  appointed, a hiring push, new equipment, a station opening. Check their
  website, local news, city council minutes.
- **Fleet info.** How many stations? How many rigs? ALS or BLS? Annual call
  volume? Check their website "About" page.

#### 2. Paste your findings into Claude

Type something like this (replace with real info):

> Here's what I found on Parma Fire Department in Ohio:
>
> - Chief: Michael Lasky, firechief@cityofparma-oh.gov
> - Medical Director: Dr. Christopher Dussel, UH Hospitals
> - 7 stations, 11 apparatus, ~5,500 EMS runs/year, ALS
> - Signal: They just got a SAFER grant for 12 new firefighters (Jan 2026)
> - Tier 2 (estimated 108 intubations/year)
>
> Write me a cold email to Chief Lasky. CC Dr. Dussel if you can find his email.

#### 3. Claude writes the email

Claude will:
- Write the email in your voice (from your voice profile)
- Score it against all 6 advisors
- Check it against the anti-AI-slop rules
- Show you the final version with scores

If any advisor scores below 6, Claude rewrites before showing you.

#### 4. Review and iterate

Read the email. If something's off, just say so:

> "The opening is too generic. Use the SAFER grant."
> "Make it shorter, under 120 words."
> "I don't love the closing question. Give me two alternatives."
> "Drop the medical director, I couldn't verify his email."
> "This sounds too formal for me. Loosen it up."

Claude rewrites and re-scores.

#### 5. Send it

Copy the final email. Paste into Gmail. Add the TO and CC addresses.
Review one more time. Send.

---

## Example conversation

Here's what an actual session looks like:

**You:** I'm working on Cuyahoga Falls Fire Department in Ohio. Here's what I found:
- Chief: Fred Jackson
- Email: fjackson@cityofcf.com
- 4 stations, mix of engines and medic units
- They posted 3 firefighter/paramedic job openings last month
- About 2,800 EMS runs per year
- Medical director: unknown, couldn't find one

Write me a cold email.

**Claude:** [writes email, shows council scores, all pass anti-AI checks]

**You:** Good but the second paragraph is too long. Tighten it up.

**Claude:** [rewrites, re-scores]

**You:** That's good. I'll send it.

---

## Rules you need to know

1. **Verify every email address before sending.** Google the city staff
   directory and confirm the email actually exists on the page. Don't guess
   patterns like first.last@city.gov. Bounced emails hurt all of us.

2. **Every email gets scored by the council.** Trust the process. If Claude
   says it needs a rewrite, let it rewrite.

3. **No AI slop.** These are banned. Claude catches them, but you should
   know them too:
   - "I hope this finds you well" — never
   - "Best regards" / "Kind regards" — never. Use your name or "Talk soon"
   - Em dashes (the long dash) — never
   - "I wanted to reach out" — you already did. Say why.
   - "Don't hesitate to reach out" — nobody was hesitating
   - "Additionally" / "Furthermore" / "Moreover" to start a sentence — never
   - See the full list in `anti-ai-slop.md`

4. **Open with THEIR world.** First sentence is about the department. Their
   grant, their hiring push, their call volume. Not about IntuBlade.

5. **Keep it under 150 words.** Cold outreach. Short. Every sentence earns
   its place.

---

## Troubleshooting

**"Claude isn't using my voice"**
Make sure your voice file is uploaded to Project Knowledge. Start a new
conversation (project knowledge loads at conversation start, not mid-conversation).

**"Claude is being too generic"**
You probably didn't give it enough research. The more specific details you
paste in (chief name, station count, recent signal), the more specific the
email will be. Garbage in, garbage out.

**"Claude keeps using banned words"**
Start a new conversation. Sometimes long conversations drift. A fresh
conversation reloads all the rules.

**"The council scored my email low"**
Read the advisor feedback. Each advisor tells you WHY they scored low.
Common issues: no specific signal (Cialdini), offer not in top half
(Hormozi), sounds like a vendor not an expert (Klaff).

**"I can't find any news about this department"**
That's fine. Tell Claude: "No recent signals. Write a generic deployment
kit email for [department]. Use their fleet data." The template still works
without a signal opener.

---

## What you should NOT do

- Don't send emails Claude hasn't scored. Even if you wrote it yourself,
  paste it in and say "score this."
- Don't skip the email verification. One bounce = our domain reputation
  takes a hit.
- Don't copy-paste the same email to multiple departments. Every email is
  personalized. That's the whole point.
- Don't argue with the anti-AI-slop rules. They exist because recipients
  can spot AI-written emails and they go straight to trash.
- Don't use Claude for anything other than IntuBlade outreach in this
  project. Keep it focused.
