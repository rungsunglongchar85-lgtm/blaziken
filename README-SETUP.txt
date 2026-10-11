BLAZIKEN OFFICIAL - setup (new, separate store)

1. Supabase: create a NEW project (e.g. "blaziken"). In SQL Editor run the files in the sql folder IN ORDER 1 to 6.
2. Supabase -> Project Settings -> API: copy the Project URL and the publishable (anon) key into config.js.
3. GitHub: create a NEW repository (e.g. blaziken-official). Upload: index.html, panel-bz9m.html, config.js, preview.jpg, and the api folder (api/nick.js).
4. Vercel: Add New -> Project -> import that repository -> Deploy. Then Settings -> Domains to choose the address.
5. Supabase -> Authentication -> URL Configuration: set Site URL and Redirect URL to your new Vercel address.
6. Open the store, Sign up with username "owner". Then in Supabase SQL Editor run:
     update profiles set is_admin=true where username='owner';
7. Admin panel: your-address/panel-bz9m.html  (log in as owner). Set UPI ID, WhatsApp number, logo, banner, games and packages in Settings.
