# IntuBlade Outbound — API Credentials

Copy everything below the line into a file called `.env` in your `outbound-council` folder.

Or paste this command into your terminal (replace the value after the = sign):

```
echo 'SUPABASE_ANON_KEY=PASTE_KEY_HERE' > ~/outbound-council/.env
```

---

## .env file contents

```
SUPABASE_ANON_KEY=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.REPLACE_THIS_WITH_REAL_KEY
```

---

## What this key does

- Syncs your research to HubSpot (contacts, notes, deal stages)
- Verifies email addresses before you send
- Tracks which departments you've emailed
- Logs reply classifications (OOO, wrong person, real reply)

## Rules

- Do NOT share this key outside the IntuBlade team
- Do NOT commit it to git (the .gitignore already prevents this)
- Do NOT paste it into Claude directly — it reads it from the .env file automatically
- If the key stops working, ask Andrew for a new one
