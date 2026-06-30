# SOP: System Access Provisioning & Offboarding
**Owner:** Executive Assistant / Operations Manager
**Prepared by Judah Rivera for Jamie LeClaire** · *Sample built for this role*
**Version:** 1.0 · **Review cycle:** quarterly

## Purpose
Make sure every person gets exactly the access they need on day one, and loses all of it within hours of leaving. No orphaned logins, no paid seats sitting empty, no "wait, who still has access to that?"

## Scope
All tools the company pays for or stores data in: PM (Asana/ClickUp), Slack, M365, Google Workspace, CRM, password manager, vendor portals, finance tools.

## Roles
- **EA/Ops (me):** runs this SOP, owns the access register.
- **CEO / lead:** approves anything that adds a paid seat or admin rights.
- **Tool owner:** whoever administers a given tool if it is not me.

---

## Part A — Onboarding (new person)
**Trigger:** start date confirmed.

1. **Create the access ticket** in the PM tool from the role template (each role has a standard access list, so this is a checklist, not a guess).
2. **Provision in order:**
   - Email + calendar (M365 or Google) → 2. Password manager seat + shared collection → 3. PM tool, correct workspace and permission level → 4. Slack + right channels → 5. Role-specific tools (CRM, design, finance).
3. **Least privilege by default.** Member, not admin, unless the role template says otherwise. Admin requires CEO approval, logged.
4. **Log it** in the Access Register (person, tool, level, date granted, approver).
5. **Send the welcome doc:** logins via password manager only (never in plain Slack/email), where the SOP library lives, who to ask for what.
6. **48-hour check:** confirm they can actually get into everything. Fix gaps before they become a blocker.

## Part B — Role change
**Trigger:** promotion, team move, or scope change.

1. Compare current access to the new role template.
2. Add what is missing, **remove what is no longer needed** (this step is the one everyone skips).
3. Update the Access Register and note the reason.

## Part C — Offboarding (person leaving)
**Trigger:** last day confirmed, or immediate on involuntary exit.

**Target: full deprovision within 4 hours of the agreed cutoff.**

1. **Revoke in priority order:**
   - Password manager + force-rotate any shared/critical passwords they touched → 2. Email + calendar (set auto-reply / forward as directed) → 3. Finance + CRM + admin consoles → 4. PM tool, Slack, vendor portals.
2. **Reassign their open items** to a new owner before removing them from the PM tool, so nothing is orphaned.
3. **Reclaim paid seats** so we stop paying for empty licenses.
4. **Transfer file ownership** (Google/M365) to the manager or shared drive.
5. **Log the offboarding** in the Access Register with timestamps.
6. **24-hour audit:** confirm zero remaining active sessions or shared links tied to them.

## Access Register (the single source of truth)
| Person | Tool | Level | Granted | Approver | Revoked |
|---|---|---|---|---|---|
| *(one row per person per tool, kept current)* | | | | | |

## Why this matters
Stale access is the quiet risk in every small remote team. This SOP turns it into a checklist with timestamps, so it is provable, not hopeful.
