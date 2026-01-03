# 🧱 Brick Inventory Manager

A beautiful, mobile-friendly brick inventory management system built as a single HTML file. Perfect for brick retailers and distributors who need a simple, portable solution to manage stock and track sales on-the-go.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)

## ✨ Features

### 📦 Inventory Management
- Add, edit, and remove brick types
- Upload product images (URL-based)
- Track detailed specifications:
  - Name and pricing
  - Mass (kg)
  - Dimensions (length × width × height in cm)
  - Stock quantities
- Beautiful card-based layout with hover effects
- Responsive grid design

### 🧮 Sales Calculator
- Select brick type from dropdown
- Input quantity to sell
- Real-time calculations:
  - **Total Cost**: Automatic price calculation
  - **Total Mass**: Weight in kilograms
  - **Coverage Area**: Surface area in m²
  - **Available Stock**: Current inventory levels
- Stock validation to prevent overselling
- Separate Calculate and Sell buttons for flexibility

### 📈 Sales History
- Complete transaction log with timestamps
- Detailed sale information:
  - Brick type and quantity
  - Price per unit and total cost
  - Mass and area calculations
- Clear history option
- Chronological display (newest first)

### 💾 Data Persistence
- All data stored locally using localStorage
- No server required
- Data persists between sessions
- Works completely offline

### 📱 Mobile-Optimized
- Responsive design for all screen sizes
- Touch-friendly interface
- Optimized for Android devices
- Modern glassmorphism UI with smooth animations
- Tab-based navigation

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, etc.)
- Android device or desktop computer

### Installation

1. **Download the HTML file**
```bash
   git clone https://github.com/yourusername/brick-inventory-manager.git
   cd brick-inventory-manager
```

2. **Open the file**
   - On Android: Download and open `brick-manager.html` in your browser
   - On Desktop: Double-click the HTML file or drag it into your browser

That's it! No installation, no dependencies, no server setup required.

## 📖 How to Use

### Adding Bricks to Inventory

1. Navigate to the **📦 Inventory** tab
2. Fill in the brick details:
   - Picture URL (optional)
   - Name
   - Price per unit
   - Mass (kg)
   - Total amount in stock
   - Dimensions (X, Y, Z in cm)
3. Click **➕ Add Brick**

### Editing or Deleting Bricks

- Click **✏️ Edit** on any brick card to modify details
- Click **🗑️ Delete** to remove a brick from inventory
- Changes are saved automatically

### Making a Sale

1. Go to the **🧮 Calculator** tab
2. Select the brick type from dropdown
3. Enter the quantity to sell
4. Click **🧮 Calculate** to preview totals
5. Click **💰 Sell** to confirm the sale
6. Confirm the transaction in the popup dialog

The system will:
- Automatically deduct from inventory
- Calculate total cost, mass, and area
- Add the transaction to sales history

### Viewing Sales History

1. Navigate to the **📈 History** tab
2. View all past transactions with details
3. Use **🗑️ Clear History** to remove all records

## 🎨 UI Features

- **Modern Gradient Background**: Purple gradient with glassmorphism effects
- **Card-Based Layout**: Clean, organized brick display
- **Smooth Animations**: Hover effects and transitions
- **Modal Dialogs**: Elegant edit interface
- **Responsive Grid**: Adapts to any screen size
- **Empty States**: Friendly messages when no data exists

## 💡 Use Cases

- **Brick Retailers**: Manage inventory and track sales
- **Construction Suppliers**: Quick stock checks and calculations
- **Distributors**: Mobile inventory management
- **Small Businesses**: Simple, no-cost inventory solution
- **Personal Projects**: Track building materials

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Structure and layout
- **CSS3**: Modern styling with gradients, flexbox, and grid
- **JavaScript (Vanilla)**: Logic and functionality
- **localStorage API**: Data persistence

### Browser Compatibility
- ✅ Chrome (Android & Desktop)
- ✅ Firefox (Android & Desktop)
- ✅ Safari (iOS & macOS)
- ✅ Edge
- ✅ Opera

### Data Storage
All data is stored locally in your browser using the localStorage API:
- `bricks`: Array of brick inventory items
- `salesHistory`: Array of completed sales transactions

**Note**: Data is device-specific. Clearing browser data will remove all stored information.

## 🔒 Privacy & Security

- **No Data Collection**: All data stays on your device
- **No Internet Required**: Works completely offline
- **No Account Needed**: Start using immediately
- **Local Storage Only**: Your data never leaves your browser

## 📝 Data Backup

Since data is stored locally, consider:
1. Periodically backing up your browser data
2. Exporting localStorage data if needed
3. Keeping a copy of the HTML file safe

## 🐛 Known Limitations

- No cloud sync between devices
- No multi-user support
- Image URLs must be publicly accessible
- Data tied to specific browser/device
- No export to CSV/Excel (can be added as feature)

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

1. **Report Bugs**: Open an issue describing the problem
2. **Suggest Features**: Share ideas for improvements
3. **Submit Pull Requests**: Add new features or fix bugs
4. **Improve Documentation**: Help make the README better

### Development Setup

1. Fork the repository
2. Make your changes to the HTML file
3. Test thoroughly on mobile and desktop
4. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with ❤️ for brick retailers and distributors
- Inspired by the need for simple, mobile inventory management
- Thanks to all users providing feedback and suggestions

## 📧 Contact

Have questions or suggestions? Feel free to:
- Open an issue on GitHub
- Contact: nuryyewkerim123@gmail.com

## 🗺️ Roadmap

Potential future enhancements:
- [ ] Export data to CSV/Excel
- [ ] Print-friendly sales receipts
- [ ] Barcode/QR code scanning
- [ ] Multi-currency support
- [ ] Dark/Light theme toggle
- [ ] Backup/Restore functionality
- [ ] Multiple warehouse support
- [ ] Low stock alerts

---

**Made with 🧱 by [Kerim]**

*If you find this project helpful, please give it a ⭐ on GitHub!*
