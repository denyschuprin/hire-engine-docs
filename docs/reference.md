# Reference & Troubleshooting

A quick reference for the status labels you'll see and answers to common
questions.

## Company stages

| Stage | Meaning |
|---|---|
| **Pending** | Just added; information gathering is queued. |
| **Enriching** | Reading the company's websites now. |
| **Enriched** | Information collected; ready to create the profile. |
| **Generating** | Drafting the profile text. |
| **Generated** | Draft ready to review, edit and approve. |
| **Publishing** | Sending the profile to Kununu. |
| **Published** | Profile draft saved on Kununu. |
| **Failed** | Something didn't finish; you can retry. |

## Source statuses

| Status | Meaning |
|---|---|
| **Pending** | Waiting to start. |
| **Running** | Reading the page now. |
| **Completed** | Finished successfully. |
| **Failed** | Couldn't finish; use **Retry**. |

## Job statuses

| Status | Meaning |
|---|---|
| **Pending** | Collected, not yet chosen to publish. |
| **Selected** | Chosen for the next publish run. |
| **Publishing** | Being sent to Kununu now. |
| **Published** | Live on Kununu. |
| **Failed** | Kununu rejected it; use **Retry**. |
| **Removed** | Marked to be deleted from Kununu on the next run. |

## Common questions

??? question "I added a company but the Sources tab is empty."
    Collection takes a moment to begin. Wait a few seconds, or click **Enrich
    Now** at the top of the company page.

??? question "One source failed - can I still continue?"
    Yes. As long as one source succeeded, the company becomes **Enriched** and
    you can create the profile. Retry the failed source anytime from its card.

??? question "Why can't I click *Generate Profile*?"
    Generation needs the company to be **Enriched** first (at least one source
    completed). Run **Enrich Now** and wait for it to finish.

??? question "My profile edits disappeared after I regenerated."
    Edited sections are normally **locked** automatically and kept. If a section
    wasn't locked, regeneration can rewrite it. Lock a section with its lock
    icon to protect it, then regenerate again.

??? question "Publishing the profile to Kununu failed."
    Two usual causes: the **Kununu session expired** (reconnect it on the
    **Credentials** tab) or the **Profile UUID** is missing or wrong (set it on
    the **Kununu Profile** tab). Fix the cause and publish again.

??? question "The *Scrape Jobs* button is greyed out."
    The company needs a **Career URL**. Add it via **Edit** on the company, then
    return to the **Jobs** tab.

??? question "A job won't publish."
    Open the job and check for missing required fields - **city**, **country**
    and **apply URL** are all needed. Fill them in, save, then publish again.
    The job's **history** (the **Show** link) explains the exact error.

??? question "Why is the career page showing *coming soon*?"
    The public career page only shows content once the profile is **approved**.
    Approve it on the **Generated Content** tab.

## Need more help?

If something isn't covered here, contact your Hire Engine point of contact with
the company name and the step you were on - that's enough to get you a quick
answer.
