# Periodic-Name-Builder

An interactive web application that converts names into combinations of chemical elements from the periodic table.



## 🌟 Features

- Convert any name into periodic table elements
- Interactive element cards with detailed information
- Animated UI elements for enhanced user experience
- Hover tooltips showing element details
- Responsive design for all device sizes
- Keyboard support (Enter key functionality)
- Beautiful gradient background
- Elegant error handling with SweetAlert2 notifications

## 🚀 Demo

Try names like:
- "Clara" → [Cl][Ar][A]
- "Francis" → [F][Ra][N][Ci][S]
- "Nick" → [Ni][C][K]

## 💻 Technologies Used

- HTML5
- CSS3 (with animations and flexbox)
- JavaScript (ES6+)
- SweetAlert2 for notifications
- CSS Custom Properties for theming
- CSS Animations for smooth transitions

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/alanjoshy/Periodic-Name-Builder
```

2. Navigate to the project directory:
```bash
cd ElementalNames
```

3. Open `index.html` in your preferred browser

## 🎯 How It Works

The application uses a recursive algorithm to break down names into valid chemical elements. For example:
1. Takes user input (name)
2. Converts it to lowercase for processing
3. Recursively searches for valid element combinations
4. Displays results with animated element cards
5. Shows detailed element information on hover

## 🎨 Customization

You can customize the appearance by modifying the CSS variables:

```css
:root {
    --primary-color: #646cff;
    --background-gradient: linear-gradient(135deg, #f0f2f5 0%, #e2e8f0 100%);
    --box-shadow: 0 4px 20px rgba(0,0,0,0.1);
    /* Add more custom properties as needed */
}
```

## 📱 Responsive Design

The application is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones
- Various screen sizes and orientations

## ⚡ Performance

- Optimized animations for smooth performance
- Efficient recursive algorithm for name checking
- Minimal external dependencies
- Responsive images and layout

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 🎉 Acknowledgments

- Periodic Table data sourced from official chemical databases
- UI inspiration from modern periodic table designs
- SweetAlert2 for beautiful alert dialogs

## 🐛 Known Issues

- Some uncommon names might not have valid element combinations
- Limited to standard periodic table elements
- Does not support special characters

## 📞 Contact


Project Link: [https://github.com/yourusername/ElementalNames](https://github.com/alanjoshy/Periodic-Name-Builder)

---

Made with ⚡ by Alan Joshy
