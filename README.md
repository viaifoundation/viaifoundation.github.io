VI AI Foundation TTS CDN
This public repository hosts static assets for the VI AI Foundation TTS Devotional Audio service, served at tts-cdn.viaifoundation.org via GitHub Pages. The frontend is at tts.viaifoundation.org (Cloudflare Pages), and the backend API is at tts-api.viaifoundation.org/api/ (IONOS VPS).
Project Structure

assets/: Logo (logo.png), favicons (favicon.ico, favicon-16x16.png, favicon-32x32.png).
index.html: Minimal page for GitHub Pages deployment.
CNAME: Configures GitHub Pages domain (tts-cdn.viaifoundation.org).
README.md: This documentation.

Setup

Clone:
git clone git@github.com:viaifoundation/viaifoundation.github.io.git
cd viaifoundation.github.io


Deploy to GitHub Pages:

In GitHub (https://github.com/viaifoundation/viaifoundation.github.io/settings/pages):
Source: main branch, folder /.
Custom domain: tts-cdn.viaifoundation.org.


Add CNAME in Cloudflare DNS: tts-cdn.viaifoundation.org → viaifoundation.github.io.


Push:
git add .
git commit -m "Initial TTS CDN setup"
git push origin main



Contact

Email: contact@viaifoundation.org
Phone: 707-560-1777
Address: PO Box 3333, Saratoga, CA 95070

License
MIT License