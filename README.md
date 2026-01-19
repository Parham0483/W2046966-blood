# Majid Group - My First Web Development Project

A charity website built during my introduction to HTML, CSS, and JavaScript. This was my first hands-on project learning web development fundamentals.

**Course**: Web Design - University of Westminster  
**Role**: Frontend Developer (Student 1)

---

## 🎯 What I Built

A multi-page charity website focused on addressing world hunger, featuring:
- **Splash Screen** with animated countdown timer
- **E-commerce Shop** with dynamic cart and form validation
- **Content Page** with smooth scrolling and responsive layout
- **Custom Navigation** with hover effects and animations

---

## 💻 Technologies Used

- **HTML5** - Page structure and semantic elements
- **CSS3** - Styling, layouts, and animations
- **JavaScript** - Interactivity and form validation

---

## 🌟 Key Features I Implemented

### 1. Splash Screen (`Splash.html`)
- JavaScript countdown timer (6 seconds)
- Auto-redirect to homepage
- Mission statement and team credits

### 2. Shop Page (`Shop.html`)
- Product hover effects
- Add to cart functionality
- Real-time price calculation
- Form validation (email, name, phone)

### 3. Content Page (`Content Page.html`)
- 4 educational sections on world hunger
- Quick navigation buttons
- Smooth scroll behavior
- "Back to Top" floating button
- Fully responsive (mobile-friendly)

### 4. Navigation System (`style.css`)
- Flexbox-based navbar
- Animated hover effects
- Semi-transparent background
- Centered logo and links

---

## 📚 What I Learned

### Technical Skills
✅ HTML structure and semantic tags  
✅ CSS Flexbox for layouts  
✅ JavaScript DOM manipulation  
✅ Event listeners (`onclick`, `onscroll`)  
✅ Form validation with JavaScript  
✅ Responsive design with media queries  
✅ CSS transitions and animations  
✅ Timer functions (`setInterval`, `setTimeout`)

### Key Code Snippets

**Countdown Timer**
```javascript
function countDown() {
    var count = 6;
    var countdownInterval = setInterval(function() {
        count--;
        if (count >= 0) {
            countDisplay.textContent = count + "s";
        } else {
            clearInterval(countdownInterval);
        }
    }, 1000);
}
```

**Smooth Scrolling**
```javascript
function scrollToSection(sectionId) {
    var section = document.getElementById(sectionId);
    window.scrollTo({
        top: section.offsetTop - 50,
        behavior: 'smooth'
    });
}
```

**Hover Animation**
```css
.navbar ul li::after {
    content: '';
    width: 0;
    transition: 0.5s;
}
.navbar ul li:hover::after {
    width: 100%;
}
```

---

## 🚀 How to Run

1. Download the project files
2. Open `Splash.html` in any web browser
3. Or navigate directly to:
   - `Shop.html` - Shopping page
   - `Content Page.html` - Information page
   - `Page Editor.html` - My contribution summary

**No server required** - runs entirely in the browser!

---

## 📁 File Structure

```
charity-website/
├── Splash.html          # Landing page with timer
├── Shop.html            # E-commerce page
├── Content Page.html    # Educational content
├── Page Editor.html     # My portfolio page
├── style.css            # Main stylesheet
└── images/              # Project images
```

---



## 📱 Responsive Design

The site adapts to mobile devices:
```css
@media (max-width: 768px) {
    .section {
        flex-direction: column;
    }
}
```

---

## 🎓 Project Impact

This project taught me:
- **Problem-solving** through debugging
- **Layout design** with CSS
- **User interactivity** with JavaScript
- **Code organization** and structure
- **Responsive thinking** for different devices

It was the foundation that led me to pursue Computer Science and more advanced web development!



**Note**: This is an academic project created for learning purposes. The charity concept is fictional.
