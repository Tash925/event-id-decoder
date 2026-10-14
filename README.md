# Event ID Decoder

A searchable, single-page reference for Windows Security event IDs, written in plain English for SOC analysts.

Each event card explains what the event means, why an analyst should care, how urgent it usually is, and which events to check next.

## Features

- Search by event ID (e.g., `4625`) or keyword (e.g., `kerberos`)
- Filter by category: Logon, Account Management, Kerberos, Process, Persistence, Defense Evasion
- Severity badges: Info / Watch / High
- **4624** logon type table, including type 9 (NewCredentials) and its pass-the-hash relevance
- **4625** failure status codes, plus how to tell password spraying, username guessing, and brute force apart
- Related-event links between cards

## Events covered

4624, 4625, 4634, 4647, 4648, 4672, 4688, 4697, 4698, 4719, 4720, 4722, 4724, 4725, 4726, 4728, 4732, 4740, 4756, 4768, 4769, 4771, 4776, 1102, 7045, 4104

## How to run

No install or build step. Download the HTML file and open it in any browser.

## How it was built

Built with [Cursor](https://cursor.com) for MLH Global Hack Week: Hacktoberfest. Cursor scaffolded the app from a single prompt, and I refined it through follow-up prompts, adding the logon-type and failure-code tables and correcting the triage guidance for accuracy.

## Disclaimer

This is a study and quick-reference tool. Verify details against Microsoft's official security auditing documentation before relying on them in an investigation.

## Author

Tasha Sumo · [DataSec Chronicles](https://datasecchronicles.com)
