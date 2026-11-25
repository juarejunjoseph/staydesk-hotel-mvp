# staydesk-hotel-mvp

Local hotel workflow prototype. Run `python3 -m http.server 8765 --bind 127.0.0.1 --directory .` and visit http://127.0.0.1:8765.

Guest kiosk, staff dashboard and housekeeping share browser LocalStorage on the same origin. Staff password: `demo123`. Airbnb demo reference: `AIR-DEMO`. Payments and concierge alerts are simulations. Use fictional details and placeholder images only. Walk-in references appear in Admin; use Open guest to resume them.

This is a fresh implementation because the original ChatGPT sandbox HTML was unavailable. Real authentication, shared database, live calendar/payment/notification integrations and secure photo/code storage are not included. The demo permits arrival before 3 PM for testing. Image retention runs when the app opens or settings are saved; it requires the browser to be opened, not a background service.
