# Income & Expenses Tracker

A beautiful, responsive web application for tracking income and expenses with visual financial insights and multiple theme options.

![Income & Expenses Tracker](https://img.shields.io/badge/Version-2.0.0-green.svg)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🌟 Features

### 💰 Core Functionality
- **Simple Income/Expense Tracking**: Add and manage financial transactions easily
- **Real-time Calculations**: Automatic totals and net balance calculations
- **Dual Currency Display**: View amounts in both standard and million formats
- **Data Persistence**: All data saved locally in your browser
- **Print Reports**: Generate printable financial summaries

### 🎨 Visual Features
- **Multiple Themes**: Choose from 4 beautiful color themes:
  - 🏢 Professional (Blue)
  - 😊 Happy (Yellow)
  - 🧘 Calm (Light Blue)
  - ⚡ Energetic (Orange)
- **Interactive Charts**: Visual income vs expenses comparison with animated bars
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Clean UI**: Modern, intuitive interface with smooth animations

### 📊 Financial Insights
- **Visual Comparison**: Side-by-side bar chart showing income vs expenses
- **Balance Indicator**: Clear visual status (Surplus/Deficit/Balanced)
- **Summary Cards**: At-a-glance financial overview with hover effects
- **Detailed Reporting**: Comprehensive table view with all calculations

## 🚀 Quick Start

### Option 1: Direct Usage
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start tracking your finances immediately!

### Option 2: Web Deployment
1. Upload the HTML file to any web server
2. Access it via your domain or hosting service
3. No additional setup required

## 📱 How to Use

### Adding Transactions
1. **Switch Tabs**: Click between Income, Expenses, and Summary tabs
2. **Enter Amount**: Type the amount in the input field
3. **Add**: Click "Add" button or press Enter key
4. **Auto-clear**: Input field clears automatically for next entry

### Managing Data
- **Edit**: Click the ✏️ icon to modify any amount
- **Delete**: Click the 🗑️ icon to remove entries
- **Print**: Generate professional reports with the Print button

### Customizing Experience
- **Change Theme**: Click color dots in header to switch themes
- **Set Report Title**: Add custom title for printed reports
- **Language Support**: Built-in support for English and Malay

## 🛠️ Technical Details

### Browser Compatibility
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers

### Data Storage
- Uses browser's localStorage
- No server-side dependencies
- Data persists between sessions
- Fully client-side operation

### File Structure
```
income-expenses-tracker/
├── index.html          # Main application file
└── README.md          # This documentation
```

## 🌍 Language Support

- **English** (Default)
- **Malay** (Bahasa Malaysia)

Switch languages by modifying the `lang` setting in the configuration section.

## 🎨 Theme Customization

### Available Themes:
1. **Professional**: Corporate blue theme for business use
2. **Happy**: Warm yellow theme for personal finance
3. **Calm**: Soothing blue theme for stress-free tracking
4. **Energetic**: Vibrant orange theme for dynamic visualization

### Custom Themes:
Modify the `THEMES` object in the JavaScript to add your own color schemes.

## 📊 Financial Calculations

### Display Formats:
- **Standard**: RM 1,234.56 (with thousand separators)
- **Million**: RM1.23 m (rounded to millions)
- **Auto-formatting**: Automatic currency formatting

### Calculations:
- **Total Income**: Sum of all income entries
- **Total Expenses**: Sum of all expense entries
- **Net Balance**: Income - Expenses
- **Visual Ratios**: Proportional bar chart display

## 🔧 Configuration

### Easy Settings Modification:
Locate the configuration section at the top of the JavaScript:

```javascript
const settings = {
  lang: 'en',           // 'en' or 'ms'
  currency: 'RM',       // Currency symbol
  mood: 'professional'  // Theme preference
};
```

## 📄 Printing Features

### Professional Reports:
- Clean, print-optimized layout
- Custom report titles
- Financial summary tables
- Remove interactive elements for clean printouts

### Print Tips:
- Set a descriptive report title before printing
- Use landscape orientation for better table layout
- Print to PDF for digital sharing

## 🛡️ Privacy & Security

### Local-Only Storage:
- All data stays on your device
- No external servers or cloud storage
- No data sharing or tracking
- Complete privacy control

### Credit Protection:
- Built-in protection for developer credits
- Prevents unauthorized modification
- Maintains attribution integrity

## 🔄 Data Management

### Export Capabilities:
- Manual data export via browser tools
- localStorage data can be backed up
- Simple JSON structure for easy migration

### Data Reset:
- Clear all data with confirmation prompt
- Start fresh when needed
- No irreversible actions

## 🐛 Troubleshooting

### Common Issues:

**Q: My data disappeared!**
A: Check if you cleared browser data or used private browsing. The app uses localStorage which can be cleared by browser cleanup tools.

**Q: Chart isn't showing properly**
A: Ensure JavaScript is enabled and you're using a modern browser.

**Q: Print layout is broken**
A: Use the print preview and adjust page margins in your browser settings.

**Q: Theme won't change**
A: Hard refresh the page (Ctrl+F5) to clear cache.

## 📈 Use Cases

### Personal Finance
- Track monthly income and expenses
- Visualize spending patterns
- Plan budgets and savings goals

### Small Business
- Monitor business cash flow
- Generate financial reports
- Track revenue and operational costs

### Freelancers
- Record project payments
- Track business expenses
- Calculate net earnings

### Students
- Learn financial management
- Track allowance and spending
- Practice budgeting skills

## 🤝 Contributing

While this is a standalone project, suggestions and improvements are welcome:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Developer

**Rashid Zainol** - JANN Sarawak 2025

## 🆘 Support

For issues, questions, or suggestions:
1. Check this README for solutions
2. Ensure you're using a supported browser
3. Verify JavaScript is enabled
4. Try refreshing the application

## 🎯 Future Enhancements

Planned features for future versions:
- [ ] Data export to CSV/Excel
- [ ] Category-based tracking
- [ ] Monthly/yearly comparisons
- [ ] Budget setting and alerts
- [ ] Data visualization charts
- [ ] Multi-currency support
- [ ] Cloud backup options

---

**⭐ If you find this project useful, please give it a star on GitHub!**

---

*Last updated: November 2025*
