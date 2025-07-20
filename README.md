# 🍽️ Catering Weekly Schedule Generator

A professional, responsive web application for creating and managing weekly catering schedules. Perfect for catering businesses, food vendors, and meal planning services.

## ✨ Features

### 📋 Business Management
- **Business Information Setup**: Add your business name, phone number, address, and additional notes
- **Week Date Configuration**: Set custom week dates or use current week with automatic date calculation
- **Professional Branding**: Clean, modern interface that reflects your business professionalism

### 🍽️ Dish Management
- **Visual Dish Upload**: Click or drag & drop dish images for easy management
- **Bulk Upload**: Add multiple dishes at once with automatic name extraction from filenames
- **Single Dish Addition**: Add individual dishes with custom names and pricing
- **Edit & Delete**: Full CRUD operations for all your dishes
- **Smart Pricing**: Automatic price formatting with dollar sign prefix

### 📅 Schedule Creation
- **7-Day Weekly View**: All days visible with responsive layout that adapts to screen size
- **Flexible Day Status**: Set days as Normal (with dishes), Off (no service), or TBD (to be determined)
- **Dropdown Selection**: Easy dish selection with sorted, searchable dropdowns
- **Drag & Drop Mode**: Alternative interface for intuitive dish assignment (currently hidden for testing)
- **Multi-Dish Support**: Add up to 3 dishes per day with visual previews

### 👀 Professional Preview
- **Real-Time Preview**: Live preview updates as you make changes
- **Responsive Design**: Optimized layout for all screen sizes (desktop, tablet, mobile)
- **Professional Styling**: Clean, modern design suitable for customer-facing materials
- **Dynamic Content**: Automatic handling of long dish names and pricing display

### 📤 Export & Sharing
- **PNG Export**: High-quality image export with professional styling and cream-beige gradient background
- **PDF Export**: Landscape A4 PDF format perfect for printing or digital sharing
- **Social Media Sharing**: One-click copy formatted text for WhatsApp, Facebook, Instagram, and other platforms
- **Cross-Platform Compatibility**: Works in all modern browsers

### 📱 Responsive Design
- **Mobile-First**: Optimized for smartphones and tablets
- **Adaptive Layout**: Automatic day arrangement based on screen size
- **Touch-Friendly**: Large buttons and touch targets for mobile devices
- **Desktop Enhanced**: Takes advantage of larger screens with multi-column layouts

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server required - runs entirely in the browser

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/catering-weekly-scheduler.git
   cd catering-weekly-scheduler
   ```

2. **Open the application**
   ```bash
   # Option 1: Open directly in browser
   open index.html
   
   # Option 2: Use a local server (recommended for full functionality)
   python -m http.server 8000
   # Then visit http://localhost:8000
   
   # Option 3: Use Live Server in VS Code
   # Right-click index.html > "Open with Live Server"
   ```

3. **Start creating schedules!**
   - Enter your business information
   - Upload dish images
   - Create your weekly schedule
   - Preview and export

## 📖 Usage Guide

### Setting Up Your Business Information
1. Fill in your business name in the "Business Information" section
2. Add your phone number or delivery information
3. Optionally add your address and any additional notes
4. Configure week dates or use the current week

### Managing Your Dishes
1. **Upload Images**: Click the upload area or drag & drop image files
2. **Single Dish**: Upload one image, fill in name and price, click "Add Dish"
3. **Bulk Upload**: Select multiple images, review auto-generated names, set prices, click "Add All Dishes"
4. **Edit Dishes**: Click "Edit" on any dish to modify name or price
5. **Delete Dishes**: Click "Delete" to remove dishes (with confirmation)

### Creating Weekly Schedules
1. **Set Day Status**: Choose Normal, Off, or TBD for each day
2. **Add Dishes**: Use the dropdown to select dishes for normal days
3. **Multiple Dishes**: Add up to 3 dishes per day
4. **Remove Dishes**: Click on selected dishes to remove them
5. **Real-Time Preview**: Watch your schedule update in the preview section

### Exporting and Sharing
1. **PNG Export**: Click "📸 Export PNG" for high-quality image
2. **PDF Export**: Click "📄 Export PDF" for printable format
3. **Social Sharing**: Click "📱 Copy for WhatsApp/Social" for formatted text
4. **Alternative Methods**: Right-click preview to save as image or take screenshots

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Styling**: Modern CSS with Flexbox and Grid layouts
- **Fonts**: Inter font family for clean, professional typography
- **Icons**: Emoji icons for intuitive interface
- **Export Libraries**: 
  - html2canvas for PNG generation
  - jsPDF for PDF creation
- **File Handling**: HTML5 File API for image uploads
- **Responsive**: CSS Media Queries for all device sizes

## 📁 Project Structure

```
catering-weekly-scheduler/
├── index.html              # Main application file
├── README.md               # This file
└── assets/                 # (Optional) Additional assets
    ├── screenshots/        # Application screenshots
    └── examples/           # Example schedules
```

## 🎨 Customization

### Color Scheme
The app uses a modern blue and cream color palette:
- Primary Blue: `#007bff`
- Secondary Blue: `#0056b3`
- Export Background: Cream-beige gradient
- Text: Various shades of gray for hierarchy

### Fonts
- Primary: Inter (Google Fonts)
- Fallback: Segoe UI, Tahoma, Geneva, Verdana, sans-serif

### Layout
- Container max-width: 1600px
- Responsive breakpoints: 1024px, 768px, 480px
- Grid columns adapt from 7-day to 2-day to 1-day layouts

## 🔧 Configuration

### Week Settings
- **Date Format**: Automatically formats dates as "Jul 14 - Jul 20"
- **Week Start**: Configurable Monday start date
- **Current Week**: Button to quickly set to current week

### Dish Management
- **Image Formats**: Supports all common image formats (JPEG, PNG, GIF, WebP)
- **Max Dishes Per Day**: Currently set to 3 (configurable in code)
- **Price Format**: Automatically adds $ prefix and formats to whole dollars

### Export Settings
- **PNG**: 2x scale, high quality, transparent background support
- **PDF**: A4 landscape, optimized for printing
- **Text Format**: Markdown-style formatting for social media

## 🐛 Troubleshooting

### Export Issues
- **PNG/PDF not working**: Ensure you're running from a web server (not file://)
- **Images not appearing in export**: Check that images are properly loaded before exporting
- **Poor quality exports**: Verify browser supports html2canvas and jsPDF libraries

### Upload Issues
- **Images not uploading**: Check file formats and sizes
- **Drag & drop not working**: Ensure you're using a modern browser with File API support

### Layout Issues
- **Days wrapping incorrectly**: Check responsive CSS and window size
- **Text cutoff**: Verify dish card heights are sufficient for content

### Browser Compatibility
- **Minimum Requirements**: 
  - Chrome 60+, Firefox 55+, Safari 12+, Edge 79+
  - JavaScript enabled
  - Local storage support (for future enhancements)

## 🚀 Future Enhancements

### Planned Features
- [ ] Save/load schedules to local storage
- [ ] Multiple week management
- [ ] Custom themes and branding
- [ ] Advanced export options
- [ ] Ingredient and nutrition information
- [ ] Customer ordering integration
- [ ] Analytics and reporting

### Technical Improvements
- [ ] Progressive Web App (PWA) support
- [ ] Offline functionality
- [ ] Database integration
- [ ] User authentication
- [ ] API for external integrations

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Setup
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Code Style
- Use consistent indentation (2 spaces)
- Comment complex functions
- Follow existing naming conventions
- Test on multiple browsers and devices

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

Created with ❤️ for the catering community.

## 🙏 Acknowledgments

- Inter font by Google Fonts
- html2canvas library for image generation
- jsPDF library for PDF creation
- Modern CSS techniques and responsive design patterns

## 📞 Support

If you encounter any issues or have questions:
1. Check the troubleshooting section above
2. Look through existing GitHub issues
3. Create a new issue with detailed description
4. Include browser version and steps to reproduce

---

**Happy Scheduling!** 🍽️📅✨
