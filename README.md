# GPS Basti Kanhal — Version 15.5

Static school app with corrected contacts: filter before displaying students, include students without a mobile number, and save the first family number directly.

## Publish

Repository Settings → Pages → Deploy from a branch → main → /(root) → Save.

## Login and data

Admin signs in with the existing account email; teachers keep their existing usernames and passwords. The public source excludes the embedded encrypted student roster and personal admin email. The Supabase URL and publishable client key are browser configuration, not administrator credentials. Existing authentication and profile checks remain in place.

School records load from the existing Supabase service after sign-in. This repository contains application source only, not student records or backups. Changing website origin does not transfer browser-local data. Keep the original site available until records and attendance have been checked on the new site. Attendance in this version is stored locally and is not included in the general JSON backup; keep it on the original browser/site until a dedicated migration is implemented.
