# Database for LiveCourierTrackingIP

This directory contains the database migration files for Supabase PostgreSQL.

### Tables
- **Admins**: Stores admin user authentication data.
- **Shipments**: Tracks shipping details.
- **Tracking Events**: Logs timeline events for shipments.

### Get Started
#### 1. Supabase URL and Key
Update your environment variables with Supabase settings.

#### 2. Run Migrations
Use the SQL files in this directory to create tables.

**Example:**
```sql
CREATE TABLE admins (
    id SERIAL PRIMARY KEY,
    email VARCHAR(255) UNIQUE NOT NULL,
    password_hash TEXT NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```