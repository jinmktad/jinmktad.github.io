Lead Form COMPLETE SET
Updated: 2025-10-15T20:24:22.341997Z

FILES
-----
1) index.html
   - Submits with FormData to Apps Script
   - Success message shown inline (no redirect)
   - Debug panel: add ?debug=1 to URL to see request/response

2) Code.gs
   - Uses SHEET_ID: 1lLrDTJH3zfKmcG2FTomxkVYpeS_Uw2d4uOclqtPLSko
   - Logs via Logger.log and console.log when DEBUG=true
   - Accepts both Korean and English field names
   - HEADERS are auto-created on the first row

HOW TO USE
----------
A) Upload index.html to your GitHub Pages repo (root).
B) Paste Code.gs into your Apps Script project and Deploy as web app:
   URL should be:
   https://script.google.com/macros/s/AKfycbw9XFx5eF1tGbJ-vNDzK2J0YQkEAEMAr5-9dieFuawpVSKBPQ5Ftv2jzKqKWWpd31n8CQ/exec
C) Open your site and test. Add ?debug=1 to see debug box.

DEBUGGING
---------
- In Apps Script, open Executions to see logs (Logger.log / console.log).
- In the browser, press F12 > Network to inspect the POST request.
