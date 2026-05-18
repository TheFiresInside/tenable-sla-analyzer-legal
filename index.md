# Tenable SLA Analyzer — Privacy Policy

**Last updated:** 2026-05-18
**Applies to:** Tenable SLA Analyzer for Windows, all versions

## What the app collects from your machine

- **Tenable.io API keys** that you enter through the app's first-run dialog.
  Stored encrypted at rest under `%USERPROFILE%\.tenable_sla\` using
  Windows DPAPI (per-user, per-machine — cannot be decrypted by another
  user or on another machine). Never transmitted to anywhere other than
  `api.tenable.com` over TLS.
- **Vulnerability and asset data** that the app downloads from your
  Tenable.io tenant using the API keys you supplied. Stored locally under
  the same `%USERPROFILE%\.tenable_sla\` directory. Never transmitted
  outbound to any third party.
- **App configuration and preferences** that you set inside the GUI
  (dashboard layouts, filter presets, notification thresholds, etc.).
  Stored locally only.

## What the app does NOT collect or send

- **No telemetry.** The app does not send installation counts, usage
  analytics, crash reports, performance metrics, or any other data to
  the developer or any third party.
- **No advertising.** No advertising identifiers are read or used.
- **No third-party data sharing.** The app does not share any data
  with any third party.
- **No background data collection.** When the app is not running, no
  data is collected or transmitted.

## Network destinations the app may contact

| Destination | When | Why |
|---|---|---|
| `api.tenable.com` | Whenever you trigger an export, refresh, or scan | Your Tenable.io API — operator-supplied credentials, TLS-only |
| `feeds.cisa.gov` | When you enable KEV (Known Exploited Vulnerabilities) overlays | Public CISA KEV catalog — no credentials sent |
| `services.nvd.nist.gov` | When you enable NVD CVE enrichment | Public NIST CVE feed — no credentials sent |
| `zerodayinitiative.com` | When you enable ZDI overlays | Public ZDI feed — no credentials sent |
| `timestamp.digicert.com` | Build-time only (developer's machine) | Authenticode signature timestamping — not contacted from user installs |

No other destinations are contacted by the app.

## Children's data

The app is intended for IT and security professionals. It is not directed
at children under 13 and does not knowingly collect any data from anyone.

## Your rights

You can delete all locally stored data by removing the directory
`%USERPROFILE%\.tenable_sla\`. The app does not retain any data outside
that directory and does not retain any data on the developer's systems.

## Changes to this policy

If we change this policy in a way that affects what data is collected or
transmitted, we will publish a new version with a new "Last updated" date.

## Contact

**Developer:** Elliot Anstey
**Email:** ea.infosec@gmail.com

For privacy-related questions or to report a concern, email the address
above. We will respond within 30 days.
