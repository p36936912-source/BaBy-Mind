# BaBy Mind — website starter

## Open it
1. Extract `BaBy_Mind_Website.zip`.
2. Open `index.html` in a browser to test it.
3. To publish a simple demo with GitHub Pages, upload `index.html` to your repository and enable Pages in the repository settings.

## Included
- Pastel themed landing/login screen with tiny storage and memory characters
- Demo account sign-in / first-time local account creation
- Add, edit, delete, search, and export notes
- Responsive design for phones and computers

## Important before sharing with real customers
This is a **front-end demo**, not a secure multi-customer website. Login details and notes are saved in the visitor's browser using localStorage. This means:
- The same account does not sync across devices or browsers.
- Customers do not share a central database.
- The demo password is not protected like a real server-side password.
- Do not store sensitive or private information in this demo.

For a real public service, connect the interface to a backend such as Supabase or Firebase with server-managed authentication, per-user database rules, and secure password handling. Do not publish a real customer data service until access rules and security have been tested.
