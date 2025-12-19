# 🛡️ SBOW Infosec

A modern cyber security and hacking resource platform for sharing security research, penetration testing methodologies, vulnerability discoveries, and educational content.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![GitHub Pages](https://img.shields.io/badge/hosted-GitHub%20Pages-success)

## 🌟 Features

- **Dark Theme by Default** - Professional hacker aesthetic with light theme option
- **11 Security Categories** - Organized content across multiple security domains
- **Resource Hub** - Comprehensive collection of wordlists, methodologies, checklists, and tools
- **Responsive Design** - Mobile-friendly layout that works on all devices
- **Easy to Customize** - Simple JavaScript-based post management
- **No Database Required** - Pure HTML/CSS/JS for GitHub Pages deployment
- **SEO Friendly** - Clean semantic HTML structure

## 🚀 Getting Started

### 1. Clone or Download

```bash
git clone https://github.com/yourusername/cybersec-research-lab.git
cd cybersec-research-lab
```

### 2. Customize

Edit `index.html` and update:
- Site name and tagline
- Social media links
- Blog post entries in the JavaScript array

### 3. Deploy to GitHub Pages

```bash
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/your-repo.git
git push -u origin main
```

## ✍️ Adding New Blog Posts

### Step 1: Update index.html

Find the `blogPosts` array in `index.html` (around line 450) and add:

```javascript
{
    id: 'your-post-slug',
    category: 'web-security', // Choose from available categories
    title: 'Your Post Title',
    excerpt: 'Brief description of your post...',
    date: 'Dec 20, 2025',
    file: 'posts/your-post-slug.html'
}
```

### Step 2: Create the Post File

1. Copy an existing post from the `posts/` folder
2. Rename it to match your `file` value
3. Update the content:
   - Change the `<title>` tag
   - Update the category badge
   - Modify the post title and meta information
   - Write your content

### Step 3: Commit and Push

```bash
git add .
git commit -m "Added new post: Your Post Title"
git push
```

## 🎨 Categories

The blog supports 10 main categories:

1. **Bug Bounty** - Bug hunting tips and writeups
2. **Web Application Security** - Web vulnerabilities and exploits
3. **VAPT** - Vulnerability assessment and penetration testing
4. **Red Team** - Advanced adversary simulation techniques
5. **API Security** - REST, GraphQL, and API testing
6. **Network Security** - Network-level attacks and pivoting
7. **Mobile Security** - iOS and Android security testing
8. **Web3 Security** - Smart contract auditing
9. **AI and LLM Security** - AI/ML security research
10. **CVEs** - Vulnerability disclosures and analysis

## 📚 Resources Section

The platform includes resource pages for:

- **Wordlists** - Collections for brute-forcing and fuzzing
- **Methodology** - Step-by-step testing procedures
- **Checklists** - Comprehensive security assessment checklists
- **Tools & Scripts** - Custom security tools
- **Payloads** - Injection payloads and exploit code
- **Cheatsheets** - Quick reference guides
- **Miscellaneous** - Additional helpful resources

## 🎨 Customization

### Changing Colors

Edit the CSS variables in the `<style>` section of any HTML file:

```css
:root {
    --bg-primary: #0d1117;      /* Main background */
    --accent-primary: #58a6ff;   /* Accent color */
    /* ... other colors ... */
}
```

### Modifying Layout

The layout uses CSS Grid for the blog posts. Adjust in the `.blog-grid` class:

```css
.blog-grid {
    grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
    gap: 25px;
}
```

## 🔧 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid, Flexbox
- **JavaScript** - Vanilla JS for interactivity
- **GitHub Pages** - Free hosting

## 🤝 Contributing
Contributions are welcome! If you'd like to contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 Content Guidelines
All content should:
- Be educational and for authorized testing only
- Include proper attribution and sources
- Follow responsible disclosure practices
- Comply with applicable laws and regulations
- Include warnings about legal and ethical considerations

## ⚖️ Legal Disclaimer
This platform and all its content are provided for **educational purposes only**. 

- Unauthorized access to computer systems is **illegal**
- Always obtain **written permission** before conducting security testing
- The authors are **not responsible** for any misuse of the information provided
- Users must comply with all applicable **laws and regulations**
- Content should only be used for **authorized** and **ethical** security research

## 📄 License
This project is licensed under the MIT License

## 🙏 Acknowledgments
- Inspired by [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)
- Built for the cybersecurity community
- Thanks to all security researchers who share knowledge openly
---

**⭐ If you find this project useful, please consider giving it a star!**
Made with ❤️ by security researchers, for security researchers.
