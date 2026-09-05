# Commute dashboard

A static, privacy-safe viewer for the private Commute tracker.

**Live site:** https://jebrila2-dot.github.io/commute-dashboard/

The public repository contains only the dashboard code. It does not contain commute configuration, journey history, API keys, or an ntfy topic.

## First use

1. Open the live site.
2. Enter the private `NTFY_STATUS_TOPIC` value.
3. Leave the server as `https://ntfy.sh` and select **Save**.

The topic is stored only in that browser's local storage. The page then reads the current status directly from ntfy. Do not commit or share the topic.
