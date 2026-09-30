# 🎨 CSS Sidebar Navigation

A modern **sidebar navigation interface** built using **HTML5 and CSS3**. This project demonstrates how interactive UI behavior can be created using CSS without JavaScript.

The interface includes a full-screen background image, animated sidebar navigation, Font Awesome icons, hover effects, smooth transitions, and a CSS checkbox-based toggle mechanism.

## 🚀 Live Demo

🔗 **[View Live Demo](https://venumadhav66.github.io/CSS_Mini_Project/)**

## 📌 Project Overview

This project was developed to strengthen my understanding of **HTML structure, CSS styling, positioning, transitions, pseudo-classes, and interactive UI techniques**.

The main focus of the project is implementing a sidebar that smoothly opens and closes using the CSS `:checked` pseudo-class instead of JavaScript.

### 🎯 Key Highlights

* ✅ CSS-only sidebar interaction
* ✅ Full-screen background image
* ✅ Smooth sidebar slide animation
* ✅ Hamburger menu button
* ✅ Close button
* ✅ Navigation menu with icons
* ✅ Interactive hover effects
* ✅ Social media icons
* ✅ Google Fonts integration
* ✅ Font Awesome integration
* ✅ No JavaScript required

---

## ✨ Features

| Feature            | Implementation         |
| ------------------ | ---------------------- |
| Sidebar Navigation | HTML + CSS             |
| Open/Close Sidebar | Checkbox + `:checked`  |
| Sidebar Animation  | CSS `transition`       |
| Menu Hover Effects | CSS `:hover`           |
| Background Image   | `photo.jpg`            |
| Typography         | Google Fonts – Poppins |
| Icons              | Font Awesome           |
| JavaScript         | Not required           |

---

## 🧠 Technical Implementation

### 1. CSS Checkbox Toggle

The sidebar uses a hidden checkbox to control its open and closed state.

```html
<input type="checkbox" id="check" />
```

When the checkbox is checked, CSS moves the sidebar into view:

```css
#check:checked ~ .sidebar_menu {
    left: 0;
}
```

When the checkbox is unchecked, the sidebar remains outside the viewport:

```css
.sidebar_menu {
    left: -300px;
}
```

This demonstrates how CSS state selectors can be used to create interactive UI behavior without JavaScript.

---

### 2. Smooth Sidebar Animation

The sidebar movement is animated using CSS transitions:

```css
transition: all 0.3s linear;
```

This creates a smooth sliding effect when the sidebar opens and closes.

---

### 3. Background Image

The project uses `photo.jpg` as a full-screen background image.

```css
.main_box {
    background: url("photo.jpg");
    height: 100vh;
    background-size: cover;
    background-position: center;
}
```

The image is stored inside the project folder so that it also works correctly when deployed using GitHub Pages.

---

### 4. Interactive Hover Effects

Menu items and icons respond to user interaction using the CSS `:hover` pseudo-class.

```css
.sidebar_menu .menu li:hover {
    box-shadow: 0 0 4px rgba(255,255,255,0.5);
}
```

Additional hover effects are applied to the menu and social media icons to improve the visual interaction.

---

### 5. CSS Positioning

The project uses different CSS positioning techniques:

* `position: fixed`
* `position: absolute`
* `top`
* `left`
* `right`
* `bottom`

The sidebar is positioned using:

```css
.sidebar_menu {
    position: fixed;
    left: -300px;
    top: 0;
}
```

When opened, the sidebar changes to:

```css
left: 0;
```

---

## 🔄 How It Works

```text
User opens the webpage
        ↓
Hamburger icon is displayed
        ↓
User clicks hamburger icon
        ↓
Checkbox becomes :checked
        ↓
CSS detects the checked state
        ↓
Sidebar moves from left: -300px → 0
        ↓
User clicks close icon
        ↓
Checkbox becomes unchecked
        ↓
Sidebar returns to left: -300px
```

---

## 🛠️ Technologies Used

| Technology   | Purpose                                     |
| ------------ | ------------------------------------------- |
| HTML5        | Page structure and navigation               |
| CSS3         | Styling, layout, animations and interaction |
| Google Fonts | Poppins typography                          |
| Font Awesome | Navigation and social media icons           |
| Git          | Version control                             |
| GitHub       | Source code hosting                         |
| GitHub Pages | Project deployment                          |

---

## 📂 Project Structure

```text
CSS_Mini_Project/
│
├── index.html      # HTML structure and navigation
├── style.css       # CSS styling and sidebar functionality
├── photo.jpg       # Background image
└── README.md       # Project documentation
```

---

## ▶️ Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/VeNumadhaV66/CSS_Mini_Project.git
```

### 2. Navigate to the Project

```bash
cd CSS_Mini_Project
```

### 3. Open the Project

Open `index.html` directly in a web browser.

You can also use **Visual Studio Code + Live Server**:

1. Open the project folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

---

## 💡 Usage

1. Open the webpage.
2. Click the **hamburger menu icon** in the top-left corner.
3. The sidebar slides into view.
4. Explore the navigation menu items.
5. Hover over menu items and social media icons to see the CSS effects.
6. Click the **close icon** to hide the sidebar.

> Note: The navigation and social media links are currently placeholders using `href="#"`.

---

## 🎓 Concepts Demonstrated

This project demonstrates practical understanding of:

* HTML5 document structure
* CSS selectors
* CSS box model
* CSS positioning
* `position: fixed`
* `position: absolute`
* `height: 100vh`
* Background images
* `background-size: cover`
* `background-position`
* CSS transitions
* CSS hover effects
* `:checked` pseudo-class
* General sibling selector `~`
* Hidden checkbox technique
* External fonts
* Font Awesome icons
* CSS-only interaction
* Git and GitHub
* GitHub Pages deployment

---

## 🎯 What I Learned

Through this project, I gained practical experience in creating an interactive navigation interface using **HTML and CSS without JavaScript**.

Key learning outcomes include:

* Creating structured HTML layouts
* Understanding CSS positioning
* Creating sidebar navigation
* Using the checkbox technique for CSS interaction
* Working with pseudo-classes
* Using sibling selectors
* Creating smooth CSS transitions
* Implementing hover effects
* Working with background images
* Integrating Google Fonts
* Integrating Font Awesome
* Deploying a project using GitHub Pages
* Managing source code using Git and GitHub

---

## 🔮 Future Improvements

Possible improvements for future versions include:

* [ ] Add functional navigation links
* [ ] Improve mobile responsiveness
* [ ] Add active navigation states
* [ ] Connect social media links
* [ ] Improve keyboard accessibility
* [ ] Add JavaScript for advanced interactions
* [ ] Add dark/light theme support
* [ ] Improve overall UI design

---

## 🌐 Project & Profile Links

### 🚀 Live Project

**[View CSS Sidebar Navigation](https://venumadhav66.github.io/CSS_Mini_Project/)**

### 💻 GitHub Repository

**[CSS_Mini_Project](https://github.com/VeNumadhaV66/CSS_Mini_Project)**

### 👨‍💻 GitHub Profile

**[VeNumadhaV66](https://github.com/VeNumadhaV66)**

### 🔗 LinkedIn Profile

**[Talari Venumadhava](https://www.linkedin.com/in/talari-venu-madhava-66751b280)**

---

## 👨‍💻 Author

### Talari Venumadhava

B.Tech Graduate | Computer Science & Data Science

**GitHub:**
[VeNumadhaV66](https://github.com/VeNumadhaV66)

**LinkedIn:**
[Talari Venumadhava](https://www.linkedin.com/in/talari-venu-madhava-66751b280)

---

## ⭐ Acknowledgement

This project was created as part of my journey to strengthen my **HTML, CSS, frontend development, and Git/GitHub skills**.

---

## 📄 License

This project was created for **learning and educational purposes**.
