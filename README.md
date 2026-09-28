> Sanitized mirror of Forgejo `serhii/azeroth-dashboard`. Source code is not published here.
>
> Commit texts: `commits/`. Need the code? Email: sergeyalpatov1@gmail.com
> Source: Forgejo `serhii/azeroth-dashboard` | Synced: 2026-10-05T01:37:23Z

---

# Azeroth Container Dashboard

A simple, cyberpunk-themed web dashboard to start and stop Docker containers that have "azeroth" in their name.

## Features
- 🚀 **Start/Stop Containers**: Control your azeroth modules with one click.
- 🖥️ **Real-time Status**: Automatically refreshes container status every 5 seconds.
- 🎨 **Cyberpunk UI**: Dark theme with neon accents.

## Setup

1. **Navigate to the directory:**
   ```bash
   cd azeroth-dashboard
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **(Optional) Create test containers:**
   If you don't have any azeroth containers running, use this script to create some dummy ones:
   ```bash
   python setup_test_containers.py
   ```

4. **Run the dashboard:**
   ```bash
   python app.py
   ```

5. **Access the dashboard:**
   Open your browser and go to: `http://localhost:5000`

## Requirements
- Docker must be installed and running.
- Your user must have permission to access the Docker socket.
