

## Direct Link -  https://prvn-1.github.io/Youtube-Page-Clone/youtube.html


# 🎬 YouTube UI Clone (Responsive)

A fully responsive YouTube front-end clone built using **HTML, CSS, and JavaScript**.

This project replicates the YouTube homepage layout and watch page with responsive behavior for desktop, tablet, and mobile devices.

---

## 🚀 Features

- ✅ Fixed Header (like YouTube)
- ✅ Sidebar Navigation (Hidden on Mobile)
- ✅ Responsive Video Grid
- ✅ Clickable Thumbnails
- ✅ Dynamic Watch Page
- ✅ Embedded YouTube Player
- ✅ Mobile-Optimized Layout
- ✅ Tablet Support
- ✅ Clean CSS Structure (Separated Files)

---

## 📁 Project Structure

```

youtube-clone/
│
├── youtube.html
├── watch.html
│
├── styles/
│   ├── general.css
│   ├── header.css
│   ├── sidebar.css
│   └── viedo.css
│
├── thumbnails/
├── channel-logo/
├── icon-folder/

```

---

## 🖥️ Desktop View

- Sidebar visible
- Multi-column video grid
- Full header with search
- Clean spacing

---

## 📱 Mobile View

- Sidebar hidden
- Single-column video layout
- Simplified header
- Full-width video player (Watch Page)

---

## 🛠️ Technologies Used

- HTML5
- CSS3 (Flexbox + Grid)
- JavaScript (Vanilla JS)
- Responsive Media Queries

---

## 🔥 How It Works

- Clicking a thumbnail redirects to `watch.html`
- Video ID is passed via URL parameter (`?v=VIDEO_ID`)
- JavaScript reads the parameter and loads the YouTube embedded player dynamically

Example:
```

watch.html?v=EBa6OoMxAag

````

---

## 📌 Responsive Strategy

- CSS Grid using `auto-fill` + `minmax()`
- Media Queries for:
  - 1024px (Tablet)
  - 768px (Mobile)
  - 480px (Small Mobile)
- Sidebar hidden on small devices
- Header simplified on mobile

---

## 📷 Preview

(You can add screenshots here)

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
````

Open `youtube.html` in your browser.

---

## 📜 License

This project is created for learning purposes only.
Not affiliated with YouTube.

---

## 👨‍💻 Author

Praveen M
Frontend Developer


Push it.  
Make it public.  
Let recruiters see you know layout engineering.
```
