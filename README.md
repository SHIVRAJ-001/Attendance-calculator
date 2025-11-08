# 🎓 Attendance Calculator

A simple and elegant web-based attendance calculator to help college students track and plan their lecture attendance effectively.


- 📊 **Real-time Attendance Calculation** - Instantly calculate your current attendance percentage
- 🎯 **Multiple Target Goals** - Track progress for 75%, 80%, and 85% attendance targets
- 📈 **Smart Planning** - See exactly how many lectures you need to attend for each target
- ⏭️ **Skip Calculator** - Know how many lectures you can safely skip while maintaining your target
- ⚠️ **Alert System** - Get warnings when attendance drops below critical levels
- 📱 **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- 🎨 **Beautiful UI** - Clean and modern interface with gradient backgrounds

## 🚀 Demo

[Live Demo](#) *(Add your live demo link here)*



## 💻 Usage

1. **Enter Lectures Conducted Till Now**: Input the total number of lectures that have been conducted so far
2. **Enter Lectures Attended**: Input how many lectures you have attended
3. **Enter Total Lectures in Semester**: Input the total number of lectures planned for the entire semester
4. Click **Calculate Attendance** or press **Enter**

### Example


Lectures Conducted: 50
Lectures Attended: 45
Total Semester Lectures: 100

Results:
- Current Attendance: 90%
- Remaining Lectures: 50
- For 75%: Target Achieved ✓ (Can skip 30 lectures)
- For 80%: Target Achieved ✓ (Can skip 25 lectures)
- For 85%: Need 5 more lectures (Can skip 0 lectures)
```

## 📊 Calculation Logic

### Current Attendance
```javascript
Current % = (Attended / Conducted) × 100
```

### Lectures Needed
```javascript
Needed for X% = (X% × Total Semester) - Attended
```

### Can Skip
```javascript
If target achieved:
  Can Skip = Remaining - Needed (if positive)
  
If target not achieved:
  Can Skip = 0
```

## 🎯 Target Sections

### 📊 75% Target (Yellow Section)
- Minimum attendance requirement in most colleges
- Shows lectures needed and skippable lectures

### 🎯 80% & 85% Target (Green Section)
- Higher attendance goals
- Displays separate calculations for both targets
- Helps maintain excellent attendance record

## 🔧 Technologies Used

- **HTML5** - Structure and semantic markup
- **CSS3** - Styling with modern features
  - CSS Grid for layout
  - Flexbox for alignment
  - Gradients and animations
  - Responsive media queries
- **JavaScript (ES6)** - Logic and interactivity
  - DOM manipulation
  - Event handling
  - Mathematical calculations



## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

## 📝 Future Enhancements

- [ ] Add subject-wise attendance tracking
- [ ] Export attendance report as PDF
- [ ] Dark mode toggle
- [ ] Multiple semester tracking
- [ ] Save history using localStorage
- [ ] Add graphs and charts
- [ ] Mobile app version
- [ ] Multi-language support

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Shivraj**



## 🙏 Acknowledgments

- Inspired by the need to help students manage their attendance effectively
- Thanks to all college students who face attendance challenges
- Built with ❤️ for the student community

## 📞 Support

If you have any questions or need help, please:
- Open an issue on GitHub


---

⭐ If you find this project helpful, please give it a star!

**Made with ❤️ by Shivraj**
