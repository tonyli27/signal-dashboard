# Signal Dashboard

Static site auto-published from the local `signal_dashboard/` pipeline (5min markets / BTC). Updated daily at 09:00 HKT after the scheduled batch run.

- **Live site**: https://TonyLI27.github.io/signal-dashboard/
- **Source pipeline**: `signal_dashboard/run_all.py` (private, not in this repo)
- **What's published**: only the latest `output/<date>/` snapshot, copied into `docs/latest/`. Past dates are not archived here.

Updates are pushed by `signal_dashboard/_publish.py` after `generate_html.py` finishes.
