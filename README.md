# BROD Tenders Registration System

Live tender bidding registration for companies.

## Deployed At
https://brodgerstraders.github.io/tender-registration/

## Features
- Professional company registration form
- Real-time Telegram notifications to Brydon
- Mobile responsive design
- Instant form validation

## Local Testing
```bash
open index.html
# or
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Data Backup
All submissions are saved to browser localStorage and can be exported:
```javascript
// In browser console:
window.showRegistrations()
```

## Next Steps
- Connect to PostgreSQL backend (offshore dev)
- Add payment processing
- Add tender listing & browsing
- Add application workflow
