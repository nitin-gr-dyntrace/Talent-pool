# 🎯 Talent Pool Scout

**Check if the talent exists before you open the role.**

A simple, browser-based recruiter tool that reads a Job Description, generates a LinkedIn Recruiter boolean search string, and helps you assess whether a talent pool actually exists — before committing to open a requisition.

---

## 🌐 Live Tool

👉 **[Open Talent Pool Scout](https://nitin-gr-dyntrace.github.io/Talent-pool/talent_pool_scout.html)**

No login. No install. Works in any browser.

---

## What it does

| Step | What happens |
|---|---|
| Paste JD | Auto-scans the job description and fills all fields |
| Review | Check and adjust the auto-detected skills, locations |
| Generate | Get a ready-to-use LinkedIn Recruiter boolean string |
| Search | Run it in LinkedIn Recruiter, note the result count |
| Log Result | Enter the count → get a Go / Hold / Rethink signal |
| Report | One click generates a PDF report for the hiring manager |

---

## How to use it

### Step 1 — Open the tool

Go to **[https://nitin-gr-dyntrace.github.io/Talent-pool/talent_pool_scout.html](https://nitin-gr-dyntrace.github.io/Talent-pool/talent_pool_scout.html)**

Or download `talent_pool_scout.html` and open it locally — works completely offline.

---

### Step 2 — Auto-fill from JD

Paste the full job description text into the **Auto-fill from Job Description** box and click **🪄 Scan & Fill Form**.

> **Important:** Paste the JD *text*, not a URL. To get the text from a job link: open the link → Select All (Ctrl+A) → Copy → Paste here.

The tool will automatically detect:
- Role title
- Must-have skills
- Good-to-have skills
- JD keywords
- Target locations
- Experience range

Works for **any role type** — tech, HR, finance, sales, legal, ops, healthcare, and more.

---

### Step 3 — Review and adjust

Check all the auto-filled tags. Remove anything that doesn't fit. Add **Target Companies** (competitors or known talent sources) manually — the tool doesn't auto-fill this since you know your market best.

| Field | What to put |
|---|---|
| **Must-Have Skills** | Hard requirements — every candidate must have ALL of these |
| **Good-to-Have** | Preferred but not mandatory — joined with OR |
| **JD Keywords** | Key phrases from the JD that signal role fit |
| **Target Locations** | Cities or regions (use LinkedIn's Location filter for these) |
| **Target Companies** | Companies you want to source from |
| **Experience** | Years of experience range |

> **Tip:** Keep must-haves to 3–5 skills max. More than 6 and the pool shrinks dramatically.

---

### Step 4 — Generate search string

Click **🔍 Generate Search String**. You'll see:
- A **pool signal** (green/yellow/red) based on how specific your criteria are
- A syntax-highlighted **boolean string** ready to copy
- Step-by-step instructions for LinkedIn Recruiter

---

### Step 5 — Run in LinkedIn Recruiter

1. Click **Open LinkedIn Recruiter** or open it manually
2. Paste the boolean string into the **Keywords** field
3. Add locations in LinkedIn's **Location filter** (not in the keyword box)
4. Note the **total candidate count** shown at the top of results

---

### Step 6 — Log the result

Back in the tool, scroll to **Step 2 — Log Your LinkedIn Result**. Enter the count and click **📊 Log & Assess**.

The tool shows your **Go / Hold / Rethink** decision:

| Count | Signal | Meaning |
|---|---|---|
| **200+** | ✅ GO | Healthy pool — safe to open the role |
| **50–200** | ⚠️ CAUTION | Moderate — set realistic timelines |
| **< 50** | 🔴 RETHINK | Too thin — revisit requirements first |

---

### Step 7 — Generate hiring manager report

Click **📄 Generate Hiring Manager Report**. A print-ready PDF report opens with:
- Role details and experience range
- Go / Hold / Rethink signal + recommendation
- Full skills breakdown
- The boolean string used
- Ready to save as PDF and email

---

## Search History

Every search is saved automatically in your browser. Click **📋 Search History** to see all past searches with their result counts. Click any card to reload and re-run.

> ⚠️ History is saved in the browser you use. Always open the tool in the same browser (Chrome recommended) to keep your history.

---

## Tips for better results

- **Don't overload must-haves.** 3–4 is the sweet spot. More than 6 = very thin pool.
- **Locations in the filter, not keywords.** LinkedIn's Location filter is smarter than a keyword match.
- **Run broad first, then narrow.** Start with just must-haves, note the count, then add more constraints.
- **Use target companies wisely.** Add direct competitors to narrow results to pre-vetted talent.
- **Re-run periodically.** Pool sizes change. Re-check every 2–3 months for open or recurring roles.

---

## Built for recruiters

This tool replaces the manual process of crafting LinkedIn boolean strings and estimating talent pool size after receiving a JD. It takes under 3 minutes to go from a JD to a data-backed hiring decision — with a shareable report for the hiring manager.

No API keys. No logins. No AI subscription required. Works in any browser.
