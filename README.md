# PMILOC DEI Blogs

## How the System Works
1. Blog entries are stored in a Google Sheet (Title, Description, Link)
2. A Google Apps Script reads the sheet and serves the data
3. GitHub Pages hosts the display page (index.html)
4. StarChapter embeds the GitHub page via a single iframe

---

## To Add a New Blog
1. Open the Google Sheet: https://docs.google.com/spreadsheets/d/1D0z2snm8jlZdUu04kAr0moDG-4-8wiQ-2AYaF79qO0Y/edit?usp=sharing
2. Add a new row with:
   - Column A: Blog Title
   - Column B: Short description (2-3 sentences). 
               To hyperlink a word, use: &lt;a href="URL"&gt;word&lt;/a&gt;'
   - Column C: Link to the full article
3. Done — the website updates automatically

---

## Accounts You Need Access To
| Account | Used For | URL |
|---|---|---|
| Google Account | Google Sheet + Apps Script | drive.google.com |
| GitHub | Hosts the display page | github.com |
| StarChapter | Chapter website | https://pmiloc.starchapter.com/ |

---

## If the Blogs Stop Showing
1. Redeploy the Apps Script:
   - Go to script.google.com
   - Open the DEI Blog project
   - Click Deploy → New deployment → Web app
   - Execute as: Me | Who has access: Anyone
   - Copy the new URL and update it in index.html on GitHub

---

## If You Need to Update the Display Page (index.html)
1. Go to PMILOC github and open the dei repository
2. Click index.html → pencil icon to edit
3. Make your changes
4. Click Commit changes
5. Wait 2 minutes for GitHub Pages to update

---

## Key URLs
- Google Sheet: https://docs.google.com/spreadsheets/d/1D0z2snm8jlZdUu04kAr0moDG-4-8wiQ-2AYaF79qO0Y/edit?usp=sharing
- Apps Script URL: https://script.google.com/macros/s/AKfycbx57J5RersTALXp4LYM1Y-8Eh2t5RyrKu3v7rmONUey_6WgDs0kUrkQQuC8_7TfLG7j/exec
- GitHub Repository: 
- GitHub Pages URL: 
- StarChapter DEI Page:
- PMILOC DEI Page
