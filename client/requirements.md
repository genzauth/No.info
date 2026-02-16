## Packages
framer-motion | Smooth animations for dashboard elements
date-fns | Formatting timestamps for logs
clsx | Conditional class merging
tailwind-merge | Tailwind class merging utility

## Notes
Dashboard requires polling for real-time status updates (every 5-10s)
Bot status endpoint returns { status: 'online'|'offline'|'error', uptime: number, ping: number }
Query logs contain JSONB response data which needs pretty printing in the UI
