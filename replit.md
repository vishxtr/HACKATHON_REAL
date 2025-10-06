# SmartSOC Analytics - Security Operations Center

## Project Overview
A professional AI-powered Security Operations Center (SOC) dashboard with real-time threat detection, analytics, and incident response capabilities.

## Setup Information
- **Language**: Python 3.11
- **Server**: Simple HTTP server serving static HTML files
- **Port**: 5000 (frontend webview)
- **Entry Point**: `server.py`

## Project Structure
- `analytics-login.html` - Login page with autofill (admin/secure123)
- `landing.html` - Landing page (default page at /)
- `index.html` - Main SOC dashboard
- `analytics.html` - Analytics dashboard
- `app.py` - Streamlit app (alternative interface)
- `phishing_module/` - Phishing detection module
- `server.py` - HTTP server for static files

## How to Run
The server automatically starts on port 5000 and serves static HTML files.
- Navigate to `/analytics-login.html` for the login page
- Default credentials are pre-filled: admin/secure123

## Recent Changes (October 6, 2025)
- ✅ Added autofill functionality to login page (username: admin, password: secure123)
- ✅ Configured HTTP server to serve static files on port 5000
- ✅ Set up deployment configuration for autoscale
- ✅ Added cache-control headers to prevent caching issues

## User Preferences
- Simple static file serving for the frontend
- Login credentials should autofill for easy demo access
