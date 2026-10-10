# Customization and publishing checklist

- [ ] Confirm whether this repository is for Meraki Realtors & Interiors or another Instagram account.
- [ ] Replace `YOUR-GITHUB-USERNAME` in `.claude-plugin/plugin.json` and `.claude-plugin/marketplace.json`.
- [ ] Edit `templates/brand.md` with the exact Instagram handle, website, WhatsApp/lead destination, approved listings, verified credentials, and allowed public proof.
- [ ] Copy the completed brand profile to `~/.claude/instagram/brand.md`.
- [ ] Complete `templates/voice.md` and copy it to `~/.claude/instagram/voice.md`.
- [ ] Test at least one Reel, one caption, and one profile audit in Claude Code.
- [ ] Review generated content for factual accuracy and local compliance before posting.

## Important limits

This repository is a prompt/skill pack plus local text-processing scripts. It is not a hosted agent, does not connect an Instagram account by itself, and does not automatically publish posts, send DMs, scrape accounts, or guarantee leads. Any separate integration should use official APIs where available and require explicit approval.
