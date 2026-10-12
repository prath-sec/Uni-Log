# Uni Log

Credits, grades, exam attempts and timetable for the M.Sc. Cybersecurity at Saarland University.
Requirements follow the Study Regulations of 25 February 2021.

Your link: **https://prath-sec.github.io/Uni-Log/**

## Put it on GitHub
1. Go to https://github.com/new
   - Repository name: `Uni-Log` (capital U and L, with the dash)
   - **Public** → **Create repository**
2. Click **uploading an existing file**.
3. Unzip `Uni-Log.zip` and drag in **all 7 files** (the files, not a folder):
   `index.html, manifest.json, sw.js, icon-180.png, icon-192.png, icon-512.png, README.md`
   → **Commit changes**. `index.html` must sit directly in the file list.
4. **Settings → Pages** → Source **Deploy from a branch** → Branch **main**, folder **/ (root)** → **Save**.
5. Wait 1–3 minutes until **Actions** shows a green ✓.

## Install on iPhone
1. Open **Safari** → `https://prath-sec.github.io/Uni-Log/`
2. **Share → Add to Home Screen** → keep the name `Uni Log` → **Add**.

It opens full screen and works offline. All data stays on your iPhone.

## Backups
Settings (⚙︎) → **Download backup file** → share sheet → **Save to Files** (iCloud Drive is safest).
To restore: **Upload backup file** and pick the .json file.
Data from the Claude version doesn't carry over automatically: download a backup there and upload it here.

## Updating later
Upload the new `index.html` over the old one. Also raise the version in `sw.js` (`uni-log-v1` → `uni-log-v2`) so the iPhone picks up the change.
