# Kununu Credentials

Before Hire Engine can publish on Kununu, it needs permission to act on the
company's behalf. There are **two** separate credentials, used for two different
jobs:

| Credential | Used for |
|---|---|
| **Kununu Profile Session** | Saving the employer **profile** draft on Kununu. |
| **Kununu Jobs API token** | Publishing **job listings** to Kununu. |

You'll find both on the **Credentials** tab of a company.

!!! info "Your secrets are safe"
    All credentials are **encrypted** and stored securely. After you save one,
    it's never shown back to you in full - only a masked hint (like
    `j****@example.com` or `••••1234`).

## Kununu Profile Session

This lets Hire Engine save profile drafts. The easiest, most reliable way to set
it up is to log in through a browser window.

1. On the **Credentials** tab, find the **Kununu Profile Session** card.
2. Click **Connect in Browser**.
3. A browser window opens. **Complete the Kununu login** there as you normally
   would.
4. Hire Engine detects the successful login and saves the session
   automatically. The card shows **Session: Connected**.

!!! tip "Testing the connection"
    Click **Test Connection** anytime to confirm the session still works. You'll
    get a green confirmation or a clear message (for example, if the session has
    expired and you need to connect again). Use **Update Session** to reconnect.

## Kununu Jobs API token

This lets Hire Engine publish job listings.

1. On the **Credentials** tab, find the **Kununu Jobs API** card.
2. Click **Add** (or **Update**).
3. Paste the **bearer token** into the field.
4. Click **Save**.
5. Click **Test Connection** to confirm it works.

!!! warning "The Jobs test needs the Profile UUID"
    Testing the Jobs token also requires the **Kununu Profile UUID** to be set
    (you'll enter that on the **Kununu Profile** tab - see
    [Publishing the Profile](publishing-profile.md)). Set the UUID first, then
    test the token.

## When is each one needed?

- Setting up the **Profile Session** → required before
  [publishing the profile](publishing-profile.md).
- Setting up the **Jobs API token** → required before
  [publishing jobs](jobs.md).

A green **Verified** badge with a date means the credential was tested
successfully.

---

Next: **[Publishing the Profile](publishing-profile.md)**.
