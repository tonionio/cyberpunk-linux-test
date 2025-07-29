# 🤖 NEURAL LINK: Linux Essentials Assessment Protocol

A cyberpunk-themed interactive test for Linux fundamentals with neon aesthetics and futuristic UI design.

![Cyberpunk Theme](https://img.shields.io/badge/Theme-Cyberpunk-00ff88?style=for-the-badge&logo=linux)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

<div align="center">

## 🎮 [**🚀 LIVE DEMO**](https://tonionio.github.io/cyberpunk-linux-test/)

*Experience the cyberpunk aesthetic while mastering Linux fundamentals*  
**No installation required - runs directly in your browser**

</div>

---

## ⚡ Features

- **🌆 Cyberpunk Aesthetic**: Neon green/pink color scheme with glow effects
- **📱 Responsive Design**: Works on desktop, tablet, and mobile devices
- **🧠 40 Linux Questions**: Comprehensive test covering essential Linux commands
- **📊 Progress Tracking**: Visual progress bar and question counter
- **🎯 Interactive Results**: Choose to review answers or restart test
- **✅ Answer Review Mode**: See correct/incorrect answers with color coding
- **🔄 Reusable**: Take the test multiple times to improve your score

## 🚀 Quick Start

### Option 1: Live Demo (Recommended)
**[Try it instantly →](https://tonionio.github.io/cyberpunk-linux-test/)**

### Option 2: Local Setup
```bash
git clone https://github.com/tonionio/cyberpunk-linux-test.git
cd cyberpunk-linux-test
# Open index.html in your browser
```

### Option 3: Direct Download
Download `index.html` and open in any modern web browser 

## 🎮 How to Use

1. **Start Assessment**: Click through 40 Linux essentials questions
2. **Navigate**: Use Previous/Next buttons to move between questions
3. **Select Answers**: Click on your choice (A, B, C, or D)
4. **Submit**: Complete all questions and submit for scoring
5. **View Results**: See your hacker status based on performance:
   - 🏆 **90%+**: Elite Hacker Status
   - 🥈 **80-89%**: Advanced User
   - 🥉 **70-79%**: System Access Granted
   - 📝 **60-69%**: Basic Access Level
   - ❌ **<60%**: Access Denied
6. **Review Mode**: Choose to review wrong answers or restart

## 📚 Topics Covered

- File system navigation and permissions
- Command line utilities (`ls`, `cd`, `pwd`, `grep`, etc.)
- User management and authentication
- Process management (`ps`, system processes)
- Network configuration and SSH
- File compression and archiving
- Shell scripting basics
- System directories and configuration files

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript**: No external dependencies except Google Fonts
- **Self-contained**: Works offline after initial load
- **Modern CSS**: Uses Flexbox, Grid, and CSS animations
- **Responsive**: Mobile-first design approach
- **Accessible**: Proper semantic HTML and keyboard navigation

## 🎨 Customization

### Changing Colors
Edit the CSS variables in the `<style>` section:
```css
/* Main theme colors */
--neon-green: #00ff88;
--neon-pink: #ff0088;
--dark-bg: #0a0a0a;
```

### Adding Questions
Modify the `questions` array in the JavaScript section:
```javascript
const questions = [
    {
        question: "Your custom question here?",
        options: ["Option A", "Option B", "Option C", "Option D"],
        correct: 1 // Index of correct answer (0-3)
    }
];
```

### Styling Modifications
- Font families: Change `'Orbitron'` and `'Source Code Pro'`
- Animations: Modify `@keyframes` rules
- Layout: Adjust Grid and Flexbox properties

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Ideas for Contributions
- Additional question sets (advanced Linux, networking, etc.)
- Different themes (matrix, synthwave, etc.)
- Sound effects and music
- Progress saving with localStorage alternative
- Multi-language support
- Difficulty levels

## 📖 Educational Use

Perfect for:
- **Students** learning Linux fundamentals
- **Bootcamps** and coding schools
- **Self-study** and certification prep
- **Study groups** and team learning
- **Instructors** looking for engaging assessment tools

## 🌟 Share the Knowledge

Love the project? Help spread the cyberpunk Linux vibes:
- ⭐ **Star this repository**
- 🔗 **Share with friends and study groups**
- 🐦 **Tweet about it** with #CyberpunkLinux

## 🐛 Bug Reports

Found a bug? Please create an issue with:
- Browser and version
- Steps to reproduce
- Expected vs actual behavior
- Screenshots if applicable

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Linux community for the foundational knowledge
- Cyberpunk aesthetic inspiration from sci-fi culture
- Google Fonts for typography
- All the choom testers who helped debug

## 🔮 Future Roadmap

- [ ] Additional question categories
- [ ] Leaderboard system
- [ ] Social sharing of scores
- [ ] Dark/light theme toggle
- [ ] Timed test mode
- [ ] Certificate generation
- [ ] Multiple choice explanations

---

<div align="center">

**Ready to jack into the matrix?** Start your Linux journey with style! 🌃

*Built with ❤️ and lots of caffeine by a fellow Linux enthusiast*

</div>
