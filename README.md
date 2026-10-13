# Sourcery US

A sourcing workbench for US recruiters who fill **tech/startup** and **skilled trades** roles (electricians, MEP, HVAC, plumbers, foremen).

**Live app:** https://handoffta.github.io/sourcery-us/

## What it does

- **Build:** paste or upload a JD (PDF, Word or text). Terms are extracted into chips you can switch off or edit: job titles with a level filter, core skills with synonyms, bonus skills, target companies, locations and exclusions. Strict / Broad modes. Strings update live.
- **Platform-specific strings** with copy buttons:
  - Both modes: LinkedIn Recruiter, LinkedIn (free, trimmed to its operator limits), Google X-ray of LinkedIn (32-word limit), and a plain-English prompt for AI sourcing tools like Juicebox.
  - Tech: Dice, GitHub X-ray, Stack Overflow X-ray, Indeed Resume.
  - Trades: Indeed Resume, ZipRecruiter, Facebook group and resume/trade-association X-rays.
- **US-specific role details:** salary + bonus + equity for tech; hourly + overtime + per diem + W-2/1099/contract-to-hire for trades; commute radius, remote states, relocation, start date, sponsorship, licenses, certifications (OSHA 10/30, NCCER, NFPA 70E, EPA 608), clearance and company stage.
- **HM intake** form (pay range required, no salary-history questions).
- **Bulk:** up to 10 JDs separated by `---`.
- **Check a string:** brackets, quotes, operators and platform support, with safe auto-fixes.
- **Compare JDs:** version A vs B side by side.
- **Tune the pool:** enter your result count and target range for specific suggestions.
- **JD quality check:** flags missing pay, unicorn requirements, degree lines, age-coded and gendered wording.
- Light and dark mode; works on phone and desktop.

## Compliance built in

Only asks "Will you now or in the future require visa sponsorship?" Never asks about citizenship, national origin or salary history. Never excludes union members.

## Notes

- Single self-contained HTML file. No build step, no backend.
- Saved searches are stored in your browser on this device.
- The AI Recruiter Kit runs only in the Claude-hosted version.

Built by [HandOffTA](https://github.com/HandOffTA).
