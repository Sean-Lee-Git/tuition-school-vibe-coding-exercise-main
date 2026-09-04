# Preparation checks

Apply `db/schema.sql` followed by `db/seed.sql` in Neon. Set `DATABASE_URL` in Render, then verify `GET /api/health` and `GET /api/db-check`. The frontend includes seeded preview data and local persistence so the responsive UI can be reviewed before cloud credentials exist.