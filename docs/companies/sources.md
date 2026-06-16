# Collecting Information (Sources)

To write a great employer profile, Hire Engine first needs to learn about the
company. It does this automatically by reading a handful of **sources**. You can
watch this happen, fix any that get stuck, and add web addresses it didn't have.

## What gets collected

As soon as you add a company, Hire Engine starts reading up to four sources:

| Source | What it collects |
|---|---|
| **Company Website** | The company description, logo, employee count, founding year and headquarters. |
| **Career Website** | The job listings and careers-page text (also detects which recruiting system the company uses). |
| **Wikipedia** | Company history and key background facts (only if a Wikipedia link is provided). |
| **XING** | Company description and employee testimonials (only if a XING link is provided). |

!!! note "Smart reading"
    For each source, Hire Engine tries the fastest method first and
    automatically falls back to more powerful methods if a page is complex or
    tries to block automated reading. You don't need to do anything - this all
    happens behind the scenes.

## The Sources tab

Open a company and click the **Sources** tab. Each source appears as a card
showing:

- Its **name** and a **status badge**:
    - **Pending** - waiting to start.
    - **Running** - reading right now (the badge pulses).
    - **Completed** - finished successfully.
    - **Failed** - couldn't finish.
- The **web address** being read (with an **Edit URL** option).
- When it **last ran**, how many times it's run, and any error message.
- An **Extracted Data** preview - a summary of what was found (company facts,
  logo, benefits, locations, a Wikipedia snippet, and more).

!!! info "Before enrichment starts"
    If you opened the company before collection began, you'll see *"Sources
    will appear after enrichment starts."* Give it a moment, or click **Enrich
    Now** at the top of the page.

## Adding or fixing a web address

If a source has no address - or the wrong one - you can fix it:

1. On the source card, click **Edit URL**.
2. Enter the correct address (it must start with `https://`).
3. Click **Save**.
4. Hire Engine asks if you'd like to **re-collect** with the new address:
    - **Re-enrich [this source] Only** - just that one source.
    - **Re-enrich All Sources** - start over for everything.
    - **Enrich Later** - save the address without re-reading now.

## Re-collecting and retrying

- **Retry one source** - if a source **failed**, click **Retry** on its card to
  try again.
- **Re-collect everything** - click **Enrich Now** at the top of the company
  page to run all sources again.

!!! tip "Partial success is fine"
    If at least one source finishes successfully, the company moves to
    **Enriched** and you can create the profile - even if another source
    failed. You can always retry the failed one later.

---

Next: **[Creating the Profile](profile.md)**.
