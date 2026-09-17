# Chill Crew masters

The .mp4 files in Season-One/ and Shorts/ are downloaded by `Build-OfflineArchive.ps1` from the CloudFront links in
MASTERS-MANIFEST.csv (the ids are the ones in `chill-crew/CHILL-CREW-CURRENT.md` §2 as of 2026-09-17). If a row's file is
missing, run the script again (it skips files that already exist with the right size) or download the URL by hand into the
listed path. Re-run after any new master is approved — the rows are read from CURRENT.md section 2 at refresh time (nothing to edit).
