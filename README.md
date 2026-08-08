Yolanda Services frontend-first application.

Files:
- index.html: existing Yolanda homepage preserved, plus 3D intro and Employee Portal link.
- login.html: mock employee authentication.
- employee-profile.html: profile + official Yolanda Call/Message Report form.
- dashboard.html: KPI cards, Chart.js analytics, report table/filtering.
- portal.css / portal.js: portal UI and mock frontend logic.
- BACKEND_API_CONTRACT.json: backend endpoints and report fields.

Demo: employee@yolanda.test / Yolanda123! (Employee ID: YOL-001)

The frontend currently uses localStorage as a temporary mock data layer. Replace those calls with the API endpoints in BACKEND_API_CONTRACT.json when the backend is built.
