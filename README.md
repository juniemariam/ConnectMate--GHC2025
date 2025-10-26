# 💜 Connect Mate – GHC 2025

### Your Personal Networking Tool for the Grace Hopper Celebration 2025

**Connect Mate – GHC 2025** is a lightweight, privacy-friendly web app built using **Google Apps Script** and **HTML5 QR Code** that helps attendees easily capture, organize, and manage professional connections at **Grace Hopper Celebration 2025**.

With just a scan, you can instantly save a contact’s LinkedIn or portfolio link, jot down key notes, and store everything neatly in your own Google Sheet — no external database, no sign-ups, and 100% yours.

<img width="1173" height="914" alt="image" src="https://github.com/user-attachments/assets/30b57d27-8e0a-4d38-9f73-8756d008f33b" />


## 🚀 Features

- 📱 **QR Code Scanner** – Scan LinkedIn or portfolio QR codes directly from your phone’s camera.  
- 📝 **Smart Notes** – Add name, company, interest level, and follow-up notes instantly.  
- ☁️ **Auto-Save to Google Sheets** – All entries are securely stored in your own Sheet copy.  
- 🎨 **Event-Ready Design** – Responsive, mobile-first UI designed for quick use during conferences.  
- ⚙️ **No Installation Needed** – Runs entirely on the web via Google Apps Script.  
- 🔒 **Private & Personal** – Each user deploys their own copy, so your data stays yours.

## 🧠 Tech Stack

- **Frontend:** HTML, CSS (Custom UI, Purple-Pink GHC theme)  
- **QR Engine:** [html5-qrcode](https://github.com/mebjas/html5-qrcode)  
- **Backend:** Google Apps Script  
- **Storage:** Google Sheets  


## 📋 Setup Instructions (for Attendees)

Follow these steps to set up and deploy your own **Connect Mate – GHC 2025** tool: 

If you need a more details check out [Setup Guide](https://github.com/juniemariam/ConnectMate--GHC2025/blob/main/ConnectMate-SetupGuide.pdf)

1. **Open the Main Sheet**  
   Access the main project sheet here:  
   👉 [Connect Mate – GHC 2025 Main Sheet](https://docs.google.com/spreadsheets/d/1p3HXBzHMjKCXe8ZWfAu5HWDdTLVgxuRPpuU86l6GIOg/edit?gid=0#gid=0)

2. **Make Your Own Copy**  
   - In the sheet menu, click **File → Make a copy**  
   - Save it to your own Google Drive.  
   *(This will also copy the entire attached Apps Script project.)*

3. **Open the Apps Script Editor**  
   - In your copied sheet, go to **Extensions → Apps Script**.  
   - This opens the script editor containing the code (`Code.gs` and `index.html`).

4. **Deploy the Web App**  
   - In the Apps Script editor, click **Deploy → New deployment → Web app**.  
   - Under **Execute as**, choose: `Me`  
   - Under **Who has access**, choose: `Anyone with Google account`  

5. **Authorize the Script**  
   - Click **Deploy** → Sign in to your Google account.  
   - When prompted, select **Advanced → Go to “Connect Mate” (unsafe)** → **Allow**.  
   *(This is normal — it just gives your script permission to write to your sheet.)*

6. **Launch Your App**  
   - Copy the provided **Web App URL** (the `/exec` link).  
   - Open it in your browser or on your phone.


##  ✅ Your app is now live!
You can now scan QR codes, capture names and company details, and all entries will automatically be stored in **your own Google Sheet**.

💡 *Tip:* You can bookmark the `/exec` link on your phone’s home screen to use it quickly during GHC!

