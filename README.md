# Signal V2 dashboard

Public read-only paper research snapshot. No trade controls, local services, credentials, or database are hosted here.

Data is published one-way every five minutes during market hours and hourly outside market hours. A stopped publication displays STALE. Market closed is not a feed failure.

The local SQLite database remains authoritative. Hosting is independent of trading and EOD. Snapshot updates deploy through workflow_dispatch without committing market data to Git history.
