SMART RECALL TRACKER — INSTALLABLE PWA

FILES
- index.html: complete app
- manifest.json: install metadata
- sw.js: offline app-shell caching
- icon-192.png and icon-512.png: app icons

IMPORTANT ANDROID INSTALLATION
1. Upload all six files to one folder in a static HTTPS host.
   Free option: GitHub Pages (https://pages.github.com/)
2. Make sure index.html is at the published site root (or open its folder URL).
3. Open the HTTPS URL in Chrome on Android.
4. Wait for the page to load once while online.
5. In Chrome, tap ⋮ > Install app (or Add to Home screen > Install).
6. Launch Smart Recall from the new home-screen icon.

Acode's local file preview is useful for editing, but PWA installation and service workers
require HTTPS (or localhost). Opening index.html as a file will not enable installation.

DATA
- Topics and completion history are stored in this browser's localStorage.
- Data stays on this device/browser profile; it is not cloud-synced.
- Use All Topics > Export backup regularly.
- Clearing browser/site data may erase saved topics. Export backups first.

REVISION SCHEDULE
The five revisions are automatically calculated at +1, +3, +7, +14 and +30 days
from the First Read Date. The Today page includes due and overdue incomplete reviews.
