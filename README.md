# Investigation Platform V1

Simple personal investigation + cloud journey frontend.

Features: domain-based investigations, create/search/filter, investigation pages, cloud journey entries, localStorage persistence.

Initial domains: Cloud, Logistics, Startup.

Run: `python3 -m http.server 8000`

Architecture path: Browser → JavaScript/localStorage → later FastAPI → PostgreSQL → Docker → Linux → Cloud.
