# 🌍 Bukittinggi Tourism Website

## 📌 Introduction
Bukittinggi Tourism is a website designed to showcase tourist destinations in Bukittinggi, Indonesia.  
This project allows users to explore different locations, view images, check travel details, and even subscribe for updates.  

---

## 📂 Project Structure
```
root/
│── index.html          # Main homepage
│── page.html           # Destination details page
│── assets/
│   ├── css/
│   │   ├── styles.css  # Main styles file
│   │   ├── swiper-bundle.min.css  # Styles for image slider
│   ├── img/            # Directory for images
│   ├── js/
│   │   ├── main.js     # Main JavaScript file
│   │   ├── scrollreveal.min.js  # Scroll animation script
│   │   ├── swiper-bundle.min.js  # Swiper.js slider script
```

---

## 🔧 Technologies Used
- **HTML5** – Page structure  
- **CSS3** – Styling and layout  
- **JavaScript (ES6)** – Interactive features  
- **Swiper.js** – Image slider  
- **ScrollReveal.js** – Scroll animations  
- **Google Maps API** – Interactive maps integration  

---

## 🚀 Features
✅ Interactive homepage with navigation and sections  
✅ Image slider to highlight popular destinations  
✅ Dark mode toggle for a better viewing experience  
✅ Interactive scroll animations  
✅ Google Maps integration for precise location details  
✅ Newsletter subscription feature  

---

## ✏️ How to Edit & Customize

### 🖼️ 1. Adding a New Destination
1. Open `index.html`.  
2. Locate the `<!-- DISCOVER -->` section.  
3. Add a new destination inside `<div class="swiper-wrapper">`:  
   ```html
   <div class="discover__card swiper-slide">
       <img src="assets/img/new-destination.jpg" alt="New Destination" class="discover__img">
       <div class="discover__data">
           <h2 class="discover__title">New Destination</h2>
           <span class="discover__description">Location Name</span>
       </div>
   </div>
   ```
4. Save and refresh your browser.

---

### 🎨 2. Changing Website Colors (Theme)
1. Open `styles.css`.  
2. Modify the **CSS variables** in `:root`:
   ```css
   :root {
       --first-color: #1A3636;  /* Primary color */
       --first-color-second: #40534C;  /* Secondary color */
       --title-color: hsl(156, 64%, 18%);
       --text-color: hsl(156, 24%, 35%);
       --body-color: hsl(156, 100%, 99%);
   }
   ```
3. Save changes and refresh the page.

---

### ✍️ 3. Editing Content & Text
- **Homepage (`index.html`)**  
  - Change **main heading**: Find `<h1 class="home__data-title">...</h1>` and edit the text.  
  - Update **welcome message**: Modify `<p class="about__description">...</p>` in the About section.  

- **Details Page (`page.html`)**  
  - Edit descriptions: Find `<p class="about__description">...</p>` and update the content.  
  - Modify **entry fees & transportation** in `<div class="table-container">`.  

---

### 🏨 4. Adding a New Hotel
1. Open `page.html`.  
2. Find the `<!-- Hotel List -->` section.  
3. Add a new hotel entry:
   ```html
   <div class="hotel-item">
       <img src="assets/img/hotel.jpg" alt="Hotel Thumbnail">
       <h3>Hotel Name</h3>
       <div class="hotel-actions">
           <button class="btn view-btn">View</button>
           <button class="btn map-btn">Maps</button>
       </div>
   </div>
   ```
4. Save and refresh the page.

---

### 🌙 5. Enabling/Disabling Dark Mode
- **To enable dark mode by default**, open `main.js` and add:
  ```js
  document.body.classList.add('dark-theme');
  ```
- **To remove dark mode functionality**, delete:
  ```js
  document.getElementById('theme-button').addEventListener("click", () => { ... });
  ```

---

### 🗺️ 6. Updating Google Maps Location
1. Open `page.html`.  
2. Find the `<iframe>` that displays the map.  
3. Replace the `src` attribute with a new **Google Maps Embed URL**.  

---

## 🚀 Deployment
To deploy this project:
1. Upload all files to your web hosting service.  
2. Or deploy via **GitHub Pages**:  
   - Go to **Settings** → **Pages**  
   - Select the **main branch** and save.  
   - Your site will be available at:  
     `https://yourusername.github.io/your-repo-name/`  

---

## 🏗️ Contributing
We welcome contributions! Feel free to:
- Open an **Issue** for bugs and feature requests.  
- Fork the project and submit a **Pull Request**.  

---

## 📜 License
This project is **open-source** and available under the [MIT License](LICENSE).  

---

🚀 *Enjoy exploring Bukittinggi! If you have any questions, feel free to reach out!*  

