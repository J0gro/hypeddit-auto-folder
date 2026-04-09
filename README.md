# 🎵 SoundCloud Auto-Folder Sync

This script automates adding an entire SoundCloud playlist into a specific folder of your Hypeddit Bypasser browser extension. Instead of manually clicking on hundreds of songs, this macro does it for you!

## ⚠️ Prerequisites
This script **only** works in combination with the [Hypeddit Bypasser](https://chromewebstore.google.com/detail/hypeddit-bypasser-2025/jekicbaadnjidjfjdbognommgdpjcipe) browser extension, which adds the orange `+` button to SoundCloud.

## 🚀 Installation & Usage

The easiest way to use this script is as a **Bookmarklet**:

1. Create a new bookmark in your browser.
2. Name it something like "SC Auto-Sync".
3. Copy the code from the `bookmarklet.js` file in this repository.
4. Paste the entire code into the **URL** (or web address) field of your bookmark and save it.
5. Create the Hypeddit Bypasser folder where you want to save the songs. You will need this name later!
6. **Let's go:** Open your SoundCloud playlist, scroll all the way to the bottom once (so all songs are loaded), and click on your new bookmark!
7. A pop-up will appear asking for the target folder. Type it in and let the script do its work. If you don't specify a folder, your songs will be saved in the default folder "Likes". 

## 💻 Console Output
When running the script, you can open your browser's developer console (`F12`). There, you'll see a live log of which song is currently being processed, along with a clear error table at the end if any songs could not be assigned.

## 📄 License
MIT License - Feel free to use and modify the code!
