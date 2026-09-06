# ZuCrypt — Releases

This repository hosts compiled release builds (installers) of **ZuCrypt**,
a Windows file encryption tool with Explorer context-menu integration.

**Source code is not published here.** ZuCrypt is closed-source,
proprietary software — this repo exists only to distribute the compiled
installer via [GitHub Releases](../../releases), which offers large file
sizes and unlimited bandwidth at no cost.

- Download the latest installer: see the [Releases](../../releases) page
- Product page / more info: https://zuczkowski.com.pl
- Author: Mirosław Żuczkowski

> **Uwaga / Note:** Twój antywirus (Windows Defender / AVG i inne) może
> ostrzec przy pierwszym uruchomieniu instalatora — to normalne dla nowych,
> niepodpisanych cyfrowo programów szyfrujących pliki (mechanizm
> szyfrowania z natury przypomina heurystykom to, co robi ransomware).
> Kliknij "Więcej informacji" → "Uruchom mimo to", żeby kontynuować.
>
> Your antivirus (Windows Defender / AVG and others) may warn you the
> first time you run the installer — this is normal for new, digitally
> unsigned file-encryption software (the encryption itself resembles what
> ransomware does, from a heuristic scanner's point of view). Click
> "More info" → "Run anyway" to continue.

## What's in the installer

`ZuCrypt-Setup.exe` is a per-user installer (no administrator rights
required) that installs ZuCrypt and adds "Encrypt"/"Decrypt" entries to
the Windows Explorer right-click context menu. Files up to 1 MB can be
encrypted/decrypted for free; larger files require a license.
