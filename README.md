# Campus Buddy Complete
This version has Register/Login, Owner/Student roles, shared timetable/assignments/notices/notes, private tasks, dark mode and PWA install.

IMPORTANT: GitHub Pages cannot be the database. Use Supabase for shared accounts/data.

SETUP:
1. Create a Supabase project.
2. Open supabase_schema.sql, replace OWNER_EMAIL_HERE with the owner's email, and run it in SQL Editor.
3. Copy Supabase Project URL and public anon/publishable key into js/config.js.
4. Upload all files/folders to GitHub Pages.
5. Register using the owner email; that account becomes Owner.
6. Owner can add timetable, assignments and notices; logged-in students see the same shared data.
7. Do not put a service_role/secret key in config.js.
