# BSC Edu Hub — GitHub Pages Ready

## Included
- `index.html` — main website
- `student.html` — working demo Student Portal
- `admin.html` — working demo Admin Panel
- `terms.html` / `privacy.html`
- `styles.css` / `app.js`
- `assets/bsc-edu-hub-logo.png`

## Demo features
### Student Portal
- Student Login button opens `student.html`
- Create Student ID
- Login using mobile + optional Student ID
- Student account is stored in browser localStorage
- My Account section

### Admin Panel
- Admin Panel button opens `admin.html`
- Demo login password: `admin123`
- Dashboard
- Add/delete study material
- Create/delete test series
- Create/delete Student IDs
- Orders placeholder
- Data persists in browser localStorage for demo/testing

### Video Editor section
The main website includes a dedicated **Video Editor — Ankit Roy** section with a portfolio button.

## Production setup still required
For a real public launch:
1. Supabase Auth for student/admin accounts
2. Supabase Database for products, students, orders and tests
3. Supabase Storage/private files for protected PDFs
4. UPI-capable payment gateway with server-side/webhook verification
5. Server-side access control for purchased content
6. Dynamic watermark using the logged-in student's name/mobile
7. Replace demo admin password with real role-based authentication

The current static version is intentionally safe for GitHub Pages testing: the demo admin password is NOT secure for a real production admin panel.


## v5 fixes
- Logo is now `assets/logo.png` and is directly referenced by all three pages.
- Main website navigation visibly includes **Student Login** and **Admin Panel**.
- `admin.html` is a standalone Admin Dashboard page with its own login screen.
- `styles.css` and `app.js` are included in the ZIP.
