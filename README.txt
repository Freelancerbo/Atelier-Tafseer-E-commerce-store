ATELIER TAFSEER - Vercel deploy

1. Go to vercel.com -> Add New -> Project.
2. Drag and drop this folder (or the unzipped files), or run "vercel" in this folder.
3. Framework preset: "Other". No build command needed. Done.

NOTES
- This is a static site (index.html). It works as-is.
- The Admin panel (add/edit products) only works inside Claude, NOT on Vercel.
  To change products on Vercel, edit the JSON inside <script id="data"> in index.html,
  or make the changes in Claude and ask for a fresh zip.
- Checkout does not take real payments yet. Orders open a WhatsApp message to your number.
- Contact: Tafseer Haider, haidertafseer30@gmail.com, +923099709880
