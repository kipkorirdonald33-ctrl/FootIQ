# FootIQ - Football AI Assistant

FootIQ is a free, football-focused AI assistant that combines **live match updates** with a **mini AI chat** for football knowledge. It is designed to be simple, reliable, and professional, perfect for fans, players, and analysts who want accurate football information at their fingertips.

## Features

- **Football Q&A:** Ask questions about rules, tactics, history, players, and clubs.  
- **Live Match Scores:** Fetches real-time football scores using the free API-Football.  
- **Cross-Platform:** Works on web and mobile (PWA compatible).  
- **Neutral & Trusted:** Answers are calm, factual, and unbiased.  
- **Zero Cost:** Uses free APIs and open-source AI models.  

## Setup Instructions

1. **Download `index.html`** from this repository.  
2. **Replace Hugging Face Key:**  
   - Open `index.html`  
   - Replace `YOUR_HUGGING_FACE_KEY` with your free Hugging Face API key  
3. **Upload to GitHub Pages:**  
   - Create a repository (e.g., `footiq`)  
   - Upload the `index.html` file  
   - Go to **Settings → Pages → Main branch → Save**  
   - Access your site at `https://yourusername.github.io/footiq/`  
4. **Enjoy FootIQ!** Ask questions and check live scores immediately.

## Notes

- Default league is Premier League (`leagueId = 39`). You can change `leagueId` in the script to follow other leagues.  
- Free APIs have rate limits; avoid excessive requests.  
- Always keep your API keys private.  

## Future Improvements

- Support multiple leagues and competitions  
- Enhance AI answers with richer examples  
- Offline static knowledge caching for faster responses  

---
