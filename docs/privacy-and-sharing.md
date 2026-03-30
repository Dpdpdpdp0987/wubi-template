# Privacy and Sharing Guide

If you publish an agent template, share structure — not a person's life.

## Never include

- API keys
- OAuth tokens
- cookies or session exports
- email addresses
- phone numbers
- SSH keys
- credential files
- private memory files from a real user
- raw chat logs
- internal migration notes with personal context

## Safer sharing pattern

Build a clean template repo instead of sanitizing a live agent repo after the fact.

## Before publishing, check

- `USER.md` has no real personal data
- `MEMORY.md` is generic or empty
- no credentials exist anywhere in the repo
- no screenshots contain sensitive info
- no sample logs contain real names, emails, or links
- no `.json` auth files are present
- no `.env` files are present

## Good public content

- blank templates
- guidance files
- example workflows with fake data
- setup instructions
- privacy notes
- architecture explanations
