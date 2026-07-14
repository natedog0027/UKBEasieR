# UKBEasieR
An R package to simplify daily use of the UK Biobank Research Analysis Platform.

## Status: Coming soon

The UKB RAP is currently offline. Package release is paused until the platform is back online and the codebase can be finalised against a working environment.

## Get notified when it's ready

Pick whichever is easier:

- **Watch this repo** — Login to GitHub, click **Watch** → **Custom** → tick **Releases** at the top of this page. GitHub will email you when v0.1.0 ships.
- **Join the mailing list** — [sign up here](https://nam10.safelinks.protection.outlook.com/?url=https%3A%2F%2Fforms.cloud.microsoft%2Fr%2F0vUS2QHz99&data=05%7C02%7Cnkennedy%40lmri.net%7Ce5aa2d54b2384131771f08dee1b79a78%7Cfdb5c40144fa493e8bc2a641d5152895%7C0%7C0%7C639196376319670707%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C40000%7C%7C%7C&sdata=t%2B0plE1hrXPBB1DToW4jU4DeDHzsRLIdh2xbHtAPp48%3D&reserved=0) with your email and I'll send a one-off announcement when the package is installable.

## What it does

UKBEasieR wraps the DNAnexus `dx` CLI into a set of R functions covering the routine tasks a UKB RAP user does day-to-day:

- **Setup** — project initialization
- **Data access** — phenotype downloads
- **Daily workflow** — saving, syncing, and backing up files between RStudio VM instance and RAP storage
- **Collaboration** — project sharing and diffing between researchers approved under the same UKB application

The goal is to reduce the number of DNAnexus concepts a user needs to hold in their head to get work done.
All access stays within the UKB RAP's permission model — the package doesn't expose data outside what your UKB application already permits.

## Talk

Presented at **ISMB 2026** (BioInfo-Core track, 14 July 2026).

## Contact

Questions or suggestions: email nkennedy@lmri.net.

## License

GPL-3
