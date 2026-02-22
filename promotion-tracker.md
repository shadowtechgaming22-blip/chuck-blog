# CPA Content Promotion Tracker

Simple tracker for cpainbox.com content across platforms.

## Articles Published

| Article | Platform | Date | Status | Traffic | Notes |
|---------|----------|------|--------|---------|-------|
| Best Email Software | cpainbox.com | 2026-02-21 | ✅ Live | - | Main affiliate page |
| Build First Email List | cpainbox.com | 2026-02-21 | ✅ Live | - | |
| Email Marketing for Coaches | cpainbox.com | 2026-02-21 | ✅ Live | - | |
| Email Segmentation | cpainbox.com | 2026-02-21 | ✅ Live | - | |
| Email Sequences | cpainbox.com | 2026-02-21 | ✅ Live | - | |
| Grow Email List | cpainbox.com | 2026-02-21 | ✅ Live | - | |
| Write Emails People Read | cpainbox.com | 2026-02-21 | ✅ Live | - | |

## Promotion Channels

- [ ] Twitter/X thread
- [ ] Reddit r/emailmarketing
- [ ] Indie Hackers
- [ ] Product Hunt submission
- [ ] Medium (check AI policy!)

## Affiliate Links

| Product | Commission | Link | Status |
|---------|------------|------|--------|
| ConvertKit | 30% recurring | TBD | Not applied |
| HubSpot | $1000/signup | TBD | Not applied |
| ActiveCampaign | $20-100 | TBD | Not applied |

## Quick Commands

```bash
# Deploy to Cloudflare Pages
cd /home/rootkit/.openclaw/workspace/cpainbox
wrangler pages deploy . --project-name cpainbox

# Check deployed site
curl -s https://cpainbox.com | head -20
```

## Affiliate Tracker

Use the affiliate tracker tool to manage program applications:

```bash
# List all programs
python3 tools/affiliate_tracker.py list

# Show details
python3 tools/affiliate_tracker.py detail convertkit

# Mark as applied
python3 tools/affiliate_tracker.py apply convertkit

# Mark as approved with link
python3 tools/affiliate_tracker.py approve convertkit "https://your.affiliate.link"

# Add earnings
python3 tools/affiliate_tracker.py earnings convertkit 15.00

# Generate promotion copy
python3 tools/affiliate_tracker.py promote convertkit
```

## Next Actions

1. Apply to ConvertKit Partner Program
2. Apply to HubSpot Affiliate  
3. Apply to ActiveCampaign Affiliate
4. Create Twitter thread promoting best article
5. Set up weekly content generation cron

---
Updated: 2026-02-21
