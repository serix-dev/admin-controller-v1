# Serix Announcements

This repository manages system status and announcements for the Serix application.

## Structure

- `config.json`: Contains system status and current announcements
- `archive/`: Historical announcements

## Configuration Format

### System Status
- `enabled`: Boolean indicating if the system is available
- `message`: Optional message shown when system is disabled
- `timestamp`: ISO timestamp of last update

### Announcements
- `id`: Unique identifier for the announcement
- `message`: The announcement text
- `timestamp`: ISO timestamp
- `severity`: "info" | "warning" | "critical"
- `allowDismiss`: Boolean indicating if users can dismiss the announcement

## Example
See `config.json` for the current configuration.
