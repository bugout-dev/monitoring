# monitoring

A simple, modular monitoring tool for tracking the health of services across various environments. Supports plugin-based checks and multiple alerting integrations.

## 🔌 Plugins

- HTTP – basic HTTP pings for availability checks.
- JSON-RPC – query latest blockchain block or custom RPC methods.
- Systemd – monitor system services (`root` or `--user`).
- Kubernetes – monitor pod statuses.

## 📡 Integrations

- SendGrid – email notifications.
- Telegram – real-time alerts in chat.
- PagerDuty – incident tracking and escalation.
- Humbug – native support for Bugout’s reports.
