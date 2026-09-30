# ParkPredict 2.0 — AI-Powered Multi-Location Smart Parking Platform

A single-page, zero-build demo of a smart parking platform for IT companies, shopping malls, hospitals, airports and commercial complexes.

## Run locally

Just open `index.html` in a browser — no build step, no dependencies. Or serve it:

```bash
npm start          # serves on http://localhost:3000
```

## Demo logins

All credentials and the demo database description live in [CREDENTIALS.md](CREDENTIALS.md).

| Portal | Login | Password | Scope |
|---|---|---|---|
| Admin | `admin` | `Admin@123` | All locations |
| Admin | `malladmin` | `Mall@123` | Shopping Mall only |
| Admin | `airportadmin` | `Airport@123` | Airport only |
| User | `EMP1024`, `EMP2043`, `VIS3007`, `VIS3008`, `EMP3050` | `demo123` | Employees & visitors |

## Notes

- All parking data is simulated demo data; AI outputs are labelled as such.
- The "database" is browser localStorage (`parkpredict2_db_v1`) — wipe & reseed from Admin → Database.
