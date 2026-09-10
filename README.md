# Commute dashboard

Static viewer for a private train archive and saved journeys.

**Live site:** [Commute dashboard](https://jebrila2-dot.github.io/commute-dashboard/)

## Using the dashboard

Sign in with your provisioned dashboard account. Choose a recent commute-day tab and direction, then select **I took this** or **I intended to take this**. If you took a different train, select it in the journey panel. Tick **Claimed** after submitting your claim on Great Northern's own portal.

Arrival delays use recorded railway arrivals, not estimates or user-entered arrival times. Missing historical evidence remains explicitly unconfirmed. The dashboard does not submit claims, accept tickets or track payments.

## Public and private data

This repository contains only static viewer assets and browser-safe connection settings. The configured route, travel windows and commute-day defaults are visible in the interface code. The Supabase publishable key identifies the project; database permissions and owner-based row security control access to private records.

Saved journeys, train observations, railway API secrets, account credentials and notification topics are not included in this repository. The private collector repository remains separate. Public registration is not offered.

## Previous dashboard

[Live advice / previous dashboard](https://jebrila2-dot.github.io/commute-dashboard/legacy.html) remains available. Its private ntfy status topic is entered by the user and stored in that browser only. Do not commit or share the topic.
