# Job Listings

Hire Engine collects a company's open jobs from its careers page and publishes
them to Kununu. You choose which jobs go live, can fine-tune each one, and can
keep them fresh automatically. Everything here is on the **Jobs** tab.

!!! info "You need a Career URL"
    Collecting jobs requires the company's **Career URL**. If it's missing, add
    it on the company (see [Adding a Company](adding-a-company.md)) - the
    **Scrape Jobs** button stays disabled until it's set.

## Collect (scrape) jobs

1. On the **Jobs** tab, click **Scrape Jobs**.
2. A box appears showing the careers-page address. Check it's correct - use
   **Open** to verify it shows the jobs list - and edit it if needed.
3. Click **Confirm & Scrape**.

Hire Engine reads the careers page in the background and fills in the jobs list.
It automatically recognises common recruiting systems (Workday, Greenhouse,
Lever, Personio and others) and, for each job, also tries to fetch the full
description, location and salary.

!!! tip "What scraping detects"
    Re-scraping is smart: **new** jobs are added, **changed** jobs are updated,
    and jobs that have disappeared from the careers page are marked **removed**
    so you can delete them from Kununu on the next publish.

## Keep jobs up to date automatically

Use the **schedule** strip at the top of the tab to re-check the careers page on
a regular basis:

- Pick an interval from the dropdown - **every 6 / 12 / 24 / 48 hours**,
  **every 7 days**, or **off**.
- The strip shows whether auto-scrape is **on**, when it **last checked**, and
  when it will check **next**.

## The jobs table

Each job appears as a row showing its **title**, **city**, **country**,
**type** (e.g. full-time), a link to the **original posting**, and a
**status badge**:

| Status | Meaning |
|---|---|
| **Pending** | Collected, not yet chosen for publishing. |
| **Selected** | Chosen - will be published on the next run. |
| **Publishing** | Being sent to Kununu right now. |
| **Published** | Live on Kununu (an **Open** link appears). |
| **Failed** | Kununu rejected it - you can retry. |
| **Removed** | Marked for deletion from Kununu on the next run. |

## Choose jobs to publish

- Tick the **checkbox** next to each job you want to publish (or use the header
  checkbox to select all).
- Selected jobs move to the **Selected** status.

## Fine-tune a job

You can edit a job in two ways:

- **Quick edit** - click the **pencil** on a row to change the title, city,
  country or type inline, then **Save**.
- **Full editor** - click a job's **title** to open the detailed editor (see
  below).

### Get the full description

Click **Get Details** on a row (or **Re-fetch** if it already has one) to pull
the complete job description, location and salary from the original posting.

### The full job editor

Opening a job (by clicking its title) gives you a two-panel screen:

- On the **left**, a link to the original job posting.
- On the **right**, every field you can adjust: title, location, **city**,
  **country**, street, ZIP, **employment type**, **apply URL**, salary range,
  and the full description.
- A **publish preview** shows exactly what will be sent to Kununu and warns you
  if a required field (city, country or apply URL) is missing.

From here you can **Save Changes**, **Get Details**, or **Publish to Kununu**
for that single job.

!!! warning "Required fields"
    A job needs a **city**, a **country** and an **apply URL** to publish. The
    editor flags anything missing before you publish.

## Publish jobs to Kununu

1. Select the jobs you want (and/or mark unwanted ones as **removed**).
2. Click **Publish Selected**. The button shows live progress, e.g.
   *"Publishing 3/10…"*.
3. When it finishes, published jobs show **Published** with an **Open** link to
   the live Kununu posting.

Publishing also **deletes** any jobs you marked **removed** from Kununu in the
same run.

!!! info "Needs the Jobs API token"
    Publishing jobs requires the **Kununu Jobs API token** and the **Profile
    UUID** to be set (see [Credentials](credentials.md)).

## Removing, restoring and retrying

- **Remove** - marks a job for deletion from Kununu on the next publish.
- **Restore** - brings a removed job back so it can be published again.
- **Retry** - re-attempts a job that **failed**.
- **Cancel run** - appears during publishing; stops the current run and resets
  in-progress jobs so you can try again.
- **Remove All Jobs** - clears the whole list for the company (handy to reset
  and scrape fresh). This removes them from Hire Engine, not from Kununu.

## See a job's history

Click **Show** on a row to expand its **publish history** - every attempt, with
the time, result, the live link, and any error message. This is the place to
look when a job won't publish.

---

Next: **[Managing Users](../admin/users.md)**.
