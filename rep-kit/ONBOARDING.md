# IntuBlade Outbound: Rep Setup Guide

Get set up in 10 minutes. No coding. No terminal. Just follow the steps.

## What this is

You're going to use Claude (an AI assistant) to research fire/EMS departments and
write personalized outreach emails. Claude knows IntuBlade's product, the sales
playbook, and how to write emails that don't sound like AI garbage.

Your job: tell Claude which department to research, review what it finds, approve
or edit the email it writes, and send it from your Gmail.

## Step 1: Get Claude Code access (2 min)

You need a Claude Max subscription ($100/month). Andrew will set this up for you.

1. Go to claude.ai/code or download the Claude Code desktop app
2. Sign in with the account Andrew created for you
3. You'll see a chat interface. That's where you'll work.

## Step 2: Set up your project (3 min)

1. Andrew will share a project link with you. Click it.
2. The project comes pre-loaded with:
   - The IntuBlade sales playbook
   - The outbound council (6 expert advisors who score every email)
   - The anti-AI-slop rules (so your emails sound human)
   - Your voice file (so emails sound like YOU, not a robot)

## Step 3: Fill out your voice profile (5 min)

Open the file `voices/voice-template.md` and fill it out. This is how Claude
learns to write like you. Be honest. If you're casual, say so. If you crack
jokes, say so. If you never say "synergy," put it in the "never say" list.

Save it as `voices/your-name.md` (e.g., `voices/danny.md`).

## You're done. Start working.

### To research a department:

Type something like:
> "Research Columbus Division of Fire in Ohio. Find me the chief, medical director,
> and any recent news I can use in an email."

Claude will search the web, find contacts, verify what it can, and give you a summary.

### To write an email:

Type something like:
> "Write a cold email to the chief of Columbus Division of Fire. Use the research
> you just did."

Claude will write the email in your voice, score it against all 6 advisors, and
show you the result. If any advisor scores below 6, it rewrites automatically.

### To improve an email:

Just talk to it:
> "Make it shorter"
> "Add the grant they just got"
> "The opening is too generic, use their new station"
> "Drop the medical director, I couldn't verify the email"

### To verify an email address:

> "Verify chief.smith@columbus.gov before I send this"

Claude will check the city staff directory and confirm the email exists.

## Rules you need to know

1. **Never send an email without verifying the recipient's address.** Bounced emails
   hurt our sender reputation. Claude will help you verify.

2. **Every email gets scored by the council.** If it scores below 7 average, Claude
   rewrites it. Trust the process.

3. **Your emails must sound like YOU, not AI.** No "I hope this finds you well." No
   "Best regards." No em dashes. No corporate filler. Claude enforces this, but
   you should know the rules too. Read `references/anti-ai-slop.md` once.

4. **Open with their world.** The first sentence of every email is about the
   department, not about IntuBlade. A recent grant, a new chief, their call volume.
   Something that shows you did your homework.

5. **Record everything.** After you research a department, tell Claude to save
   the notes. When you move to the next lead, the research should be captured.

## Common commands

| What you want | What to type |
|--------------|-------------|
| Research a department | "Research [department name] in [state]" |
| Write a cold email | "Write an email to [department]. Use the research." |
| Score an email | "Score this email against the council" |
| Rewrite in your voice | "Rewrite this in my voice" |
| Verify an email | "Verify [email address]" |
| Find the medical director | "Find the medical director for [department]" |
| Check NPI registry | "Look up [doctor name] on NPI registry in [city], OH" |
| Shorten an email | "Make this shorter. Under 150 words." |

## FAQ

**Q: Can Claude send the email for me?**
No. Claude writes the draft. You review it, copy it into Gmail, and send it yourself.
This is intentional. You own the relationship.

**Q: What if Claude can't find any recent news about a department?**
That happens with small rural departments. Tell Claude to use the generic template
(deployment kit offer) without a signal opener. Still verify contacts and CC the
medical director if you have one.

**Q: What if the council scores my email below 7?**
Claude will rewrite it automatically. If you disagree with the rewrite, tell Claude
what you want changed. You have final say.

**Q: Can I write the email myself and just have Claude score it?**
Yes. Paste your email and say "Score this against the council." Claude will give
you advisor-by-advisor feedback.

**Q: How many emails should I send per day?**
Start with 5-10. Quality matters more than volume. A 10/10 email that gets a reply
is worth more than 50 generic blasts that get ignored.
