# Publishing the Profile

Once the profile is **approved** and your **Kununu Profile Session** is
connected, you can publish the profile to Kununu. This happens on the
**Kununu Profile** tab.

## Before you publish

Make sure you have:

- [x] An **approved** profile (see [Creating the Profile](profile.md)).
- [x] A connected **Kununu Profile Session** (see [Credentials](credentials.md)).
- [x] The company's **Kununu Profile UUID** (set below).

## Set the Kununu Profile UUID

The UUID tells Hire Engine exactly which Kununu profile to update.

1. Open the **Kununu Profile** tab.
2. Paste the company's **Kununu Profile UUID** into the field
   (it looks like `00000000-0000-0000-0000-000000000000`).
3. Optionally paste the **Kununu Profile URL** as well.
4. Click **Save**. A green **Saved.** confirmation appears.

!!! note "Where to find the UUID"
    The UUID comes from the company's Kununu employer dashboard. The optional
    URL just helps point to the correct country/language version of the page.

## Preview what will be sent

Before publishing, you can review exactly what Hire Engine will send to Kununu -
every section mapped to its Kununu field, with cleaned-up social links and
videos. This lets you catch anything that looks off before going live.

## Publish the draft

1. On the **Kununu Profile** tab, click **Save draft to Kununu**.
2. The company moves to **Publishing**, and Hire Engine fills in every section
   on Kununu for you. This runs in the background.
3. The status updates on its own. When it's done you'll see a summary, e.g.
   *"Draft saved. Filled X fields, Y not found."*

!!! info "It's saved as a draft"
    Publishing saves the content as a **draft** on Kununu - it does not make it
    public on Kununu by itself. Final publishing on Kununu's side stays under
    your control.

## Checking the status

The tab shows the latest publish run's status (queued, running, completed or
failed), how many fields were filled, the profile's Kununu URL, and when it was
last published. If a run fails, the error message explains what went wrong so
you can fix it and try again.

!!! tip "If publishing fails"
    The most common causes are an **expired Kununu session** (reconnect it on
    the [Credentials](credentials.md) tab) or a **missing/incorrect UUID**.
    Fix the cause and click **Save draft to Kununu** again.

---

Next: **[Your Career Page](career-page.md)**.
