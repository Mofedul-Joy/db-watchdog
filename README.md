# db-watchdog
Every 5 min: probes Supabase auth. If it times out 3 times, restarts the project (max once per 30 min) and fails the run so GitHub emails an alert. Config lives in repo secrets.
