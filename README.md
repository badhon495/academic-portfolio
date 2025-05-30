# Academic Portfolio
<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![FormSubmit](https://img.shields.io/badge/FormSubmit-Form-00B2FF?style=flat-square)

</div>

I have created this simple academic portfolio template to showcase my research, projects, and professional experience. It is designed to be easy to use and customize, with a focus on clean design and accessibility. You can check the site live at:

**Portfolio Site:** [https://badhon495.github.io](https://badhon495.github.io)

## Features

- Pure HTML, CSS, and minimal JavaScript (no frameworks)
- Responsive design for desktop and mobile
- Dark and light mode toggle (see sun/moon icon at top right)
- Last update time shown in the footer (auto-updates via JavaScript)
- Anonymous message form (popup, powered by [FormSubmit](https://formsubmit.io))
- Modern, clean, and accessible UI
- All content is easily customizable in `index.html`
- Profile image and resume included (see `images/` and `data/` folders)
- No build step required: just edit and deploy

## Folder Structure

- `index.html` - Main portfolio page (edit this for your info)
- `css/` - All stylesheets (main: `stylesheet.css`, popup: `mail.css`)
- `js/` - JavaScript for dark mode, mail popup, and last modified time
- `images/` - Profile picture and theme icons
- `data/` - Resume PDF and other downloadable files

## How to Use

1. **Fork or clone this repository**
   - To fork: Click the "Fork" button at the top right of the GitHub repository page. This will create a copy of the repository under your own GitHub account.
   - To clone: Run the following command in your terminal (replace YOUR-USERNAME with your GitHub username):
     ```sh
     git clone https://github.com/YOUR-USERNAME/academic-portfolio.git
     ```
   - Navigate into the project directory:
     ```sh
     cd academic-portfolio
     ```
2. **Host on GitHub Pages**
   - Go to your forked/cloned repository on GitHub.
   - Click on "Settings" > "Pages" in the sidebar.
   - Under "Source", select the `main` branch and `/ (root)` folder.
   - Click "Save". GitHub will build and deploy your site. After a few minutes, your portfolio will be live at `https://YOUR-USERNAME.github.io/academic-portfolio/`.
3. **(Optional) Rename your repository for a professional URL**
   - If you rename your repository to `YOUR-USERNAME.github.io`, your portfolio will be accessible at `https://YOUR-USERNAME.github.io/` (without the `/academic-portfolio/` part), which looks more professional and is easier to share.
4. Edit `index.html` to add your own information, projects, and research
5. Replace the profile image in `images/profilePic.jpeg` and resume in `data/Demo_Resume.pdf`

## Customization Tips

- To change the popup form, edit `js/mail.js` and `css/mail.css`
- To adjust dark mode, edit `js/dark_mode.js` and CSS files
- For new sections, copy the structure of existing `<table class="section">` blocks
- All icons are from [Bootstrap Icons](https://icons.getbootstrap.com/)

## Contribution
If you find any issues or have suggestions, feel free to open an issue or submit a pull request. Contributions are welcome!