# 🎉 Event Gallery Page

A simple and responsive webpage to showcase photos from a recent event using **Google Drive** as the image hosting system.

---

## 🖼️ Live Preview

- [click here for live preview](https://event-image-sharing.vercel.app/)

> See awesome moments from the event in an embedded gallery view.

---

## ✨ Features

- 🎨 Beautiful hero banner with centered text
- 🌐 Responsive design (mobile + desktop)
- 📁 Photos displayed via Google Drive folder
- 💡 Easy to update or reuse for future events

---

## 📁 Folder Structure

```

📂 event-gallery/
├── index.html         # Main HTML file
├── banner.jpg         # (Optional) Banner background image
└── README.md          # This file

```

---

## 🔧 How to Use

1. **Clone or download this repo**
2. Replace the **Google Drive folder ID** in the `<iframe>` embed in `index.html`:
   ```html
   <iframe
     src="https://drive.google.com/embeddedfolderview?id=YOUR_FOLDER_ID#grid"
     ...
   ></iframe>
   ```

````

3. (Optional) Replace the background image in the `.banner` style:

   ```css
   background-image: url('your-banner.jpg');
   ```

---

## 📷 How to Get Google Drive Folder ID

1. Go to your Google Drive
2. Right-click your event photo folder > `Get link`
3. Make sure it’s set to **"Anyone with the link can view"**
4. Copy the folder ID from the URL:

   ```
   https://drive.google.com/drive/folders/1jSw9T_xRnh4r8ruO_n_9yJel2aZOzAhbY
                                          ↑ This is your folder ID
   ```

---

## 💡 Customization Tips

* Adjust the banner height in CSS if needed
* Change the overlay darkness using `rgba(0, 0, 0, 0.5)`
* Add a footer with contact links if desired

---

## 🧑‍💻 Built With

* HTML5
* CSS3
* Google Drive (as photo gallery backend)

---

## 🙏 Credits

Created with ❤️ by Ozioma Egole

---

## 📄 License

This project is open-source and free to use. Modify it for personal or public event galleries.

````
