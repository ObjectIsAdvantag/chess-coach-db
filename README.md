# Chess Coach Database Backups

This repository stores backups of the Chess Coach database.

## Structure

- `backups/`: Timestamped database backups
- `snapshots/`: Monthly SQL/PGN exports

## Security

⚠️ **Private Repository** - Contains personal chess game data

## Restore

```bash
# Download latest backup
git clone <this-repo>
cd chess-coach-db

# Copy to Chess Coach data directory
cp backups/latest.db ~/chess-coach/data/chess_coach.db
```

## Backup Info

Each commit message documents:
- Timestamp
- Reason for backup
- Database statistics (games, themes, size)
