# Personal Portfolio Website
Student: Adhipatya Saxena
Assignment: Responsive Personal Portfolio Website (Assignment - 1)

---

## 📌 Tools Used
- **HTML5** → For semantic page structure (`header`, `nav`, `section`, `article`, `aside`, `footer`).  
- **CSS3 (External styles.css)** → For custom styling (typography, colors, spacing, borders, hover & focus effects).  
- **Tailwind CSS (via npm build → output.css)** → For responsive design, utility-based styling, flex/grid layouts, dark mode. (Can also be done via CDN)
- **JavaScript** → For dark mode toggle, smooth page transitions, and contact form reset handling.  

---

## 🌟 Features Implemented
1. **Multi-page Structure**  
   - 3 pages: Home (`index.html`), Projects (`projects.html`), Contact (`contact.html`).  
   - Consistent navigation bar across all pages.  

2. **Semantic HTML**  
   - Proper use of semantic tags for structure and accessibility.  

3. **Navigation**  
   - Internal links between all pages.  
   - Responsive and styled navigation menu with hover effects.  

4. **Contact Form**  
   - Includes fields for Name, Email, and Message.  
   - Validation attributes (`required`, `pattern`, `type="email"`).  
   - Submit and Reset buttons with interactive states.  

5. **Projects**  
   - Table displaying project details (Name, Description, Tools Used, Status, Year).  
   - Ordered list (Skills) and unordered list (Tools) are included on the Home page.  

6. **Media Embedding**  
   - Profile image on Home page.  
   - Intro video (`intro.mp4`) and background audio (`bg-music.mp3`).  
   - Additional project demo videos (`project1.mp4`, `project2.mp4`).  

7. **Styling (External CSS + Tailwind)**  
   - Custom `styles.css` for fonts, animations, and button effects.  
   - Tailwind utility classes for responsive layouts, grids, and dark mode.  
   - Smooth transitions applied across hover, focus, and dark mode toggle.  

8. **Responsive Design**  
   - Tailwind’s responsive classes (`sm:`, `md:`, `lg:`) used.  
   - Website adapts to mobile, tablet, and desktop.  

9. **Dark Mode (Bonus)**  
   - Dark/Light mode toggle in the navbar.  
   - User preference saved in localStorage.  

10. **Page Transitions (Bonus)**  
    - Smooth fade-in and fade-out animations between pages.  

---

## 📂 Folder Structure

```
Portfolio/
├── index.html        (Home)
├── projects.html     (Projects)
├── contact.html      (Contact)
├── styles.css        (Custom CSS)
│── input.css             (Tailwind input file)
│── output.css            (Compiled Tailwind CSS)
├── profile.jpeg
├── contact-us.png
├── intro.mp4
├── bg-music.mp3
├── project1.mp4
├── project2.mp4
```
