# 🎯 Talent Pool Scout

A simple browser-based tool for recruiters to **check if a talent pool exists before opening a role**. No installs, no logins — just open the HTML file in any browser.

---

## What it does

Before you write a JD and open a req, this tool helps you answer:
> *"Is there even enough talent out there for this role?"*

You fill in the role details, it generates a ready-to-use **LinkedIn Recruiter boolean search string**, and gives you a signal on whether the pool looks healthy or too narrow.

---

## How to use it

### Step 1 — Open the tool
- Download `talent_pool_scout.html`
- Double-click it — it opens in your browser (Chrome recommended)
- No internet required after that

---

### Step 2 — Fill in the New Search form

| Field | What to put | Example |
|---|---|---|
| **Role Title** | The job title you're evaluating | `Senior Data Engineer` |
| **Must-Have Skills** | Skills every candidate MUST have | `Python`, `Apache Spark`, `SQL` |
| **Good-to-Have Skills** | Nice to have, but not mandatory | `Airflow`, `dbt`, `Kafka` |
| **JD Keywords** | Key phrases from the job description | `data pipeline`, `ETL`, `lakehouse` |
| **Target Locations** | Cities or regions to search in | `Bangalore`, `Pune`, `Remote` |
| **Target Companies** | Competitors or companies to source from | `Databricks`, `Snowflake`, `AWS` |
| **Experience** | Years of experience range | `4` to `8` |

> **How to add tags:** Type a skill, then press **Enter** or **comma (,)** to add it. Click the × on any tag to remove it.

---

### Step 3 — Generate the search string

Click **🔍 Generate Search String**.

You'll see:
- 🟢 **Green signal** — Search looks broad, good pool expected
- 🟡 **Yellow signal** — Moderate pool, may need some relaxing
- 🔴 **Red signal** — Too many must-haves, pool will be very narrow

---

### Step 4 — Run it in LinkedIn Recruiter

1. Click **"Open LinkedIn Recruiter"** — it opens Recruiter in a new tab
2. Paste the boolean string into the **Keywords** field
3. If you added locations, set those in the **Location filter** (not the keyword box — this gives better results)
4. Hit Search and note the **total candidate count** at the top

---

### Step 5 — Interpret the result

| Count | What it means |
|---|---|
| **200+** | ✅ Healthy pool — safe to open the role |
| **50–200** | ⚠️ Moderate — proceed, but sourcing may take longer |
| **< 50** | ❌ Too narrow — revisit requirements before opening |

If the pool is too narrow, try:
- Moving 1–2 must-haves to good-to-have
- Widening the location filter
- Removing very specific JD keywords

---

### Step 6 — Share with the hiring manager

Screenshot the LinkedIn Recruiter result count and share it alongside your recommendation. This is your data-backed answer to *"Can we find this person?"*

---

## Search History

Every search you run is **automatically saved** in the browser. Click the **📋 Search History** tab to see all past searches. Click any card to reload that search.

> ⚠️ History is saved in the browser you use. Always open the tool in the same browser (Chrome recommended) to keep your history.

---

## Tips for better results

- **Don't overload must-haves.** 3–4 must-have skills is the sweet spot. More than 5 and the pool shrinks fast.
- **Use target companies wisely.** Add direct competitors or known talent sources — this narrows to pre-vetted candidates.
- **Locations in the filter, not keywords.** LinkedIn Recruiter's location filter is smarter than a keyword match.
- **Run broad first, then narrow.** Start with just must-haves, note the count, then add more filters to see how the pool shrinks.

---

## Built with ❤️ for recruiters

This tool was built to replace the manual process of crafting LinkedIn boolean strings by hand after receiving a JD. It takes under 2 minutes to go from a JD to a talent pool signal.

For questions or improvements, reach out to your team.
