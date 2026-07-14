# UKBEasieR
An R package to simplify daily use of the UK Biobank Research Analysis Platform.

## Status: Coming soon

The UKB RAP is currently offline. Package release is paused until the platform is back online and the codebase can be finalised against a working environment.

## Get notified when it's ready

Pick whichever is easier:

- **Watch this repo** — Login to GitHub, click **Watch** → **Custom** → tick **Releases** at the top of this page. GitHub will email you when v0.1.0 ships.
- **Join the mailing list** — [sign up here](https://forms.gle/YOUR-FORM-ID) with your email and I'll send a one-off announcement when the package is installable.

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
