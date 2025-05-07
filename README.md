# urala777

## URL
[https://example.com](https://example.com)

## Topic Description
This is a personal portfolio website created by Létai Laura, showcasing selected graphic design works. The portfolio includes both commercial and experimental projects and serves as a platform to present design philosophy, past works, and contact information in a clean, minimal, and responsive format. The layout is structured for desktop and mobile users, with an emphasis on ease of navigation and visual clarity.

## Source of Codes
The HTML, CSS, and JavaScript used in this project were written manually by the creator. No external frameworks or libraries were used—just plain HTML, CSS, and vanilla JavaScript. Inline CSS is used for styling the hamburger menu and navigation, while JavaScript handles the responsive menu toggle functionality.


## Source of Images
All images used in this project are original works created by Létai Laura as part of her graphic design portfolio. These include branding projects, poster designs, book illustrations, and concept-driven visual works. The image files are stored locally in the `images/` folder.

## JavaScript Code Used
The project uses a **custom JavaScript function** to implement a responsive **hamburger menu toggle**. It includes a basic `debounce` timer to avoid accidental rapid toggling when clicking the menu button. The script adds or removes the `.active` class on the navigation `<ul>` to slide the menu in or out from the left side of the screen.

```javascript
let debounceTimer;
function toggleMenu() {
    clearTimeout(debounceTimer);
    debounceTimer = setTimeout(() => {
        const nav = document.querySelector('nav ul');
        nav.classList.toggle('active');
    }, 200);
}
```

## Font Used
The project uses the following fonts:
- [Source Code Pro] from [Google Fonts](https://fonts.google.com).

## Author
Létai Laura
# urala777
