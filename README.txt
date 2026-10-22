DAYFLOW v1 — SMART SCHOOL, WORK & FITNESS PLANNER

FEATURES
- Weekly repeating classes, work shifts, study sessions and other calendar events
- One-time events, including exams and deadlines
- Smart cardio/strength suggestions in open time slots (7 AM–9:30 PM)
- 10-minute buffer around existing commitments
- Mark scheduled workouts complete or log additional workouts
- Calorie, protein, steps, weight and weekly cardio tracking
- Adjustable goals; weight trend chart; automatic local saving
- Import/export JSON backup for moving data to another device
- Export a one-time calendar .ics snapshot with 15-minute reminders (if imported
  into a calendar application that honors the included alarms)
- Offline use after installation (PWA)

IMPORTANT LIMITATIONS IN VERSION 1
- All data remains on your device in browser storage; there is no user account or cloud sync.
- There is no automatic integration with Samsung Health or Google Calendar yet.
- There are no in-app push notifications, phone alarms, or automatic rescheduling yet.
  For reminders, export an .ics snapshot in Settings and import it into a calendar.
  Calendar export is not live sync; importing again may duplicate events.
- Meal calories/protein and steps must be entered manually.
- Scheduled workout sessions are only counted as completed when you mark or log them.
- Event times are in your device's local timezone. Events that cross midnight aren't supported.
- This is a planning tool, not medical advice or a clinically validated calorie calculator.

TRY IT ON A COMPUTER
Open index.html in Chrome or another modern browser. Some mobile browsers may restrict
local-file access; for reliable use, publish it as below.

INSTALL IT ON A SAMSUNG PHONE
1. Unzip this package.
2. Upload the entire dayflow-app folder to an HTTPS static host such as GitHub Pages,
   Cloudflare Pages, or Netlify. Keep all files together at the same folder path.
   Example: https://YOURNAME.github.io/dayflow-app/
3. Open the HTTPS website in Samsung's Chrome browser.
4. Tap the three-dot menu, then select "Add to Home screen" or "Install app".
5. Launch DayFlow from your home screen.
6. To get reminder alerts, use Settings > Export schedule to calendar (.ics),
   then import the file into a calendar app that supports .ics. Imported weekly
   events repeat indefinitely until you remove them from that calendar.
7. Open Settings in DayFlow and choose "Export backup" occasionally to save your data.

If your browser offers only a shortcut instead of an installable app, confirm that all
files including manifest.webmanifest, sw.js, and both icons are available over HTTPS.

PRIVACY
No analytics and no external network services are used by this version. The service
worker caches the app's static files for offline usage. Your personal entries are saved
in the current browser's localStorage. Clearing app/browser data may erase them.
