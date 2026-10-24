# skills

Personal Claude Code skills.

## gmail-cleanup
Safely free Gmail storage by bulk-trashing marketing/newsletter mail while protecting receipts, invoices, gift cards, confirmations and account mail. Archives locally before trashing and before Trash is emptied.

### Install
```bash
git clone https://github.com/jay3686/skills.git
mkdir -p ~/.claude/skills
cp -r skills/gmail-cleanup ~/.claude/skills/
```
(Windows PowerShell: `Copy-Item -Recurse skills\gmail-cleanup $env:USERPROFILE\.claude\skills\`)

### Requirements
- Claude Code with the Gmail connector and Claude in Chrome connected to the Gmail account.

### Run
Start Claude Code and say: `Use the gmail-cleanup skill to clean my Gmail.`

### Collaborate
Spot a better exclusion or a new pitfall? Sign up for a free GitHub account (https://github.com/signup), fork this repo and open a pull request, or send your GitHub username to Jay to be added as a collaborator.
