# SOSAC TV - Free YouTube Search & Download App

A completely **FREE** YouTube search application with **UNLIMITED searches forever**, **real YouTube videos**, and **MP3 downloads**. No API keys, no payments, no quotas.

## ✨ What You Have

**SOSAC TV** - One-Click YouTube Search + Download

- 🔍 Search unlimited YouTube videos
- ⬇️ Download MP3 with one tap (128 kbps, smallest file size)
- 📱 Mobile optimized (works perfectly on phone)
- 📥 Real filenames (SONG.mp3, not "audio.mp3")
- 🌐 100% FREE forever
- ♾️ Infinite scroll (endless videos)
- 🎬 YouTube embedded player (no ads)

## 🎯 How It Works

### 1. Welcome Screen (First Time)
- Enter your name once
- Never register again

### 2. Search Videos
- Search YouTube
- See infinite videos
- Tap ▶️ WATCH or ⬇️ ADD TO DOWNLOAD

### 3. Download Queue
- See all your videos
- Tap 🎵 DOWNLOAD MP3
- **Downloads instantly** (no extra pages)
- File saves as real name (e.g., SONG.mp3)

---

## 📁 Files Structure

```
SOSAC TV/
├── server.js              # Main backend server (all endpoints)
├── index.html             # Search videos page
├── download.html          # Download queue page
├── watch.html             # Video player page
├── info.html              # Welcome/registration page
├── service-worker.js      # Offline support
├── manifest.json          # PWA manifest
├── package.json           # Dependencies
├── package-lock.json      # Dependency lock
└── replit.md              # This documentation
```

---

## 🔧 Backend Routes

### Search
- `GET /search?q=query` - Search YouTube videos

### MP3 Download
- `GET /ss-downloader/download-mp3?url=YOUTUBE_URL&title=SONG_NAME` - Direct MP3 download (128 kbps)
- `GET /ss-downloader/get-info?url=YOUTUBE_URL` - Get video info

### Video Info
- `GET /video-by-url?url=YOUTUBE_URL` - Get video details

---

## 🎵 MP3 Download Feature

**One-Tap Download:**
1. Tap 🎵 DOWNLOAD MP3 button
2. Shows notification: "📥 Downloading MP3..."
3. File downloads directly to your phone
4. Saved as real filename (SONG.mp3)
5. **Quality:** 128 kbps (smallest file size ~1MB/min)

---

## 📦 Dependencies

```json
{
  "express": "^4.18.2",
  "cors": "^2.8.5",
  "play-dl": "^4.3.7",
  "youtube-search-api": "^1.1.1",
  "ytdl-core": "^4.11.5",
  "ytsr": "^3.8.4"
}
```

---

## 🚀 Deployment

Currently running on Replit with temp URL:
```
https://75dd752b-08be-458a-ba51-cde8af4a3403-00-14imejt8na59w.spock.replit.dev
```

**To get permanent 24/7 URLs:**
Deploy to Render (free tier) - works forever on your phone

---

## ✅ Features

✅ Search unlimited YouTube videos  
✅ One-tap MP3 download (128 kbps)  
✅ Real filenames (SONG.mp3)  
✅ Download queue management  
✅ Watch videos with embedded player  
✅ Offline support (Service Worker)  
✅ Progressive Web App (install on home screen)  
✅ Mobile optimized  
✅ One-time registration  
✅ 100% FREE forever

---

## 🌟 Clean Structure

- ✅ Only necessary files kept
- ✅ All temporary files deleted
- ✅ No node_modules bloat shown
- ✅ Single server for all endpoints
- ✅ Ready to deploy

---

**SOSAC TV** - Your free YouTube search & download app!

**Version:** 1.0  
**Last Updated:** November 29, 2025  
**Status:** ✅ Ready to Deploy
