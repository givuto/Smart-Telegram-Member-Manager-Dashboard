# Smart Telegram Member Manager + Dashboard

<p align="center">
  <img src="assets/dashboard-hero.png" alt="Smart Telegram Member Manager Dashboard" width="100%" />
</p>

<p align="center"><strong>Premium Telegram campaign operations platform</strong></p>
<p align="center">Live control, account orchestration, risk guardrails, and real-time reporting in one dashboard.</p>

> [!IMPORTANT]
> This repository is a public product showcase.  
> Source code is private at this time.

## What This Project Is

Smart Telegram Member Manager is a dashboard-first platform for running Telegram growth campaigns with stronger control, safety, and visibility than basic scripts.

## What Users Get

- Dashboard-based campaign control and monitoring
- Multi-account session management
- Multi-campaign architecture with templates and presets
- Smart safety automation to reduce account pressure
- Real-time progress, logs, and run analytics
- JSON + CSV reporting for operational review

## Premium Features

### Campaign Execution
- Bulk member-add campaign flow
- Multi-source support for source links
- Public source scraping (with optional aggressive mode)
- Auto-join source links during runtime
- Per-account caps and pacing controls
- Resume mode from checkpoint
- Retry-failed mode from checkpoint
- Cross-source dedupe and run-level progress tracking

### Account Operations
- Phone code request + verify flow
- 2FA-aware verification support
- Session persistence and account deduplication
- Delete account + cleanup session file
- Banned account filtering support
- Account health status tracking (ready, busy, cooling, warm-up)

### Safety and Stability
- Auto-pause on high error rate
- Stop on no-success window
- Stop on low ready-account threshold
- Stop on rate-limit burst threshold
- Auto-resume with wait + max-attempt controls
- FloodWait/PeerFlood-aware cooldown logic
- Smart Start Guard (`auto` / `suggest`)
- Safety response mode (`manual` / `auto`)

### Smart Performance System
- Auto account allocator with min/max boundaries
- Allocator expand-on-healthy control
- Allocator shrink-on-pressure control
- Adaptive concurrency backoff + recovery
- Weighted source scheduler
- Source fatigue guard with cooldown windows
- Source quality scoring panel
- Account class routing (`cold`, `warm`, `hot`)
- Promotion/demotion based on score + rate-limit history
- Fair-share governor for concurrent campaigns
- Campaign priority weighting in weighted fair-share mode

### Multi-Campaign Management
- Per-campaign settings and runtime files
- Create/update/switch/delete campaign flows
- Save/apply/delete campaign templates
- Presets: `safe`, `balanced`, `fast`
- Auto-tune from latest run report
- Free-run profile mode
- Global action: apply preset to all campaigns
- Global action: copy active settings to all campaigns
- Global action: set safety response mode for all campaigns

### Monitoring and Reporting
- Preflight checks before launch
- Dry-run plan with risk recommendations
- Live progress stream endpoint
- Real-time dashboard payload and activity logs
- Checkpoint reset action
- JSON + CSV run reports
- Error breakdown insights from latest report
- Source quality metrics: score, attempts, success, rate hits, fatigue hits
- Settings backup + restore support

### Utility Tools Included
- Send message from all accounts
- Join group/channel from all accounts
- Leave group/channel from all accounts
- Report group/channel from all accounts
- Hidden-member scrape/add helper flow

## Dashboard Screenshots

Add your image files in `assets/` with these names:

- `dashboard-hero.png`
- `dashboard-overview.png`
- `dashboard-campaigns.png`
- `dashboard-settings.png`
- `dashboard-reports.png`

| Overview | Campaigns |
|---|---|
| ![Dashboard Overview](assets/dashboard-overview.png) | ![Dashboard Campaigns](assets/dashboard-campaigns.png) |

| Settings | Reports |
|---|---|
| ![Dashboard Settings](assets/dashboard-settings.png) | ![Dashboard Reports](assets/dashboard-reports.png) |

## Typical Workflow

1. Add and verify account sessions
2. Create or select a campaign
3. Run preflight and review dry-run guidance
4. Apply preset/template and launch
5. Monitor live dashboard progress
6. Resume/retry from checkpoint when needed
7. Review reports and auto-tune next run

## Repository Status

- Public repo: product overview and screenshots
- Source code: private
- Access/release updates: posted in this repository

