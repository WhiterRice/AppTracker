# 🎯 Job Application Tracker

A beautiful, feature-rich web application for tracking job applications with interactive Sankey flow visualization. Built with vanilla HTML, CSS, and JavaScript - no frameworks required!

## ✨ Features

### 📊 Interactive Sankey Visualization
- **Flow Diagram**: Visualize your job application pipeline from Pending → Applied → Screening → Interview → Offer → Accepted
- **Terminating Outcomes**: Track applications that end in Declined, Rejected, Withdrawn, or Ghosted states
- **Real-time Updates**: Diagram automatically updates as you add or edit applications
- **Beautiful Design**: Gradient flows, hover effects, and professional styling

### 🎨 Modern Interface
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Glass Morphism UI**: Beautiful gradient backgrounds and frosted glass effects
- **Job Cards**: Clean, card-based layout with hover animations
- **Color-Coded Status**: Intuitive color scheme for different application stages and outcomes

### 📝 Comprehensive Application Management
- **Complete CRUD Operations**: Create, Read, Update, and Delete job applications
- **Inline Editing**: Click to edit any application field directly in the interface
- **Rich Data Fields**: Track company, position, salary, RTO policy, progress stage, and final outcome
- **Automatic Timestamps**: Track creation date and last updated date for every application

### 📈 Analytics & Insights
- **Statistics Dashboard**: Live stats showing Total, Active, Interview, and Offer counts
- **Advanced Sorting**: 8 different sorting options including date, company, and position
- **Timeline Tracking**: See when applications were created and last modified

### 💾 Data Management
- **JSON Import/Export**: Backup and restore your data easily
- **Local Storage**: Data persists in your browser automatically
- **Data Validation**: Import validation ensures data integrity
- **Merge or Replace**: Choose to merge imported data with existing applications

## 🚀 Getting Started

### Quick Start
1. **Download**: Clone this repository or download `index.html`
2. **Open**: Double-click `index.html` or open it in any modern web browser
3. **Start Tracking**: Begin adding your job applications immediately!

### No Installation Required
- **Pure HTML/CSS/JavaScript**: No build process, dependencies, or server required
- **Works Offline**: Fully functional without internet connection
- **Cross-Platform**: Works on Windows, macOS, Linux, and mobile devices

## 🎨 Application Stages & Color Coding

### Progress Stages
- 🔵 **Pending** (Blue-Gray) - Applications ready to submit
- 🟢 **Applied** (Blue) - Applications submitted
- 🟠 **Screening** (Orange) - Under company review
- 🟣 **Interview** (Purple) - In interview process
- 🟡 **Offer** (Golden Yellow) - Offer received

### Final Outcomes
- ✅ **Accepted** (Green) - Job offer accepted
- ❌ **Declined** (Red) - Application declined by company
- 🚫 **Rejected** (Pink) - Application rejected by company
- 👻 **Ghosted** (Gray) - No response received
- 🚪 **Withdrawn** (Gray) - Application withdrawn by candidate

## 📋 Usage Guide

### Adding Applications
1. Fill out the form with company name, position, and progress stage (required)
2. Optionally add salary range and RTO policy
3. Set a final outcome if the application process is complete
4. Click "Add Application" to save

### Editing Applications
1. Click the "Edit Application" button on any job card
2. Modify any field using the inline form
3. Click "Save Changes" to update or "Cancel" to discard changes

### Sorting & Organization
- Use the **Sort by** dropdown in the Applications section header
- Choose from 8 sorting options: creation date, update date, company, or position
- Applications update instantly when you change the sort order

### Data Export/Import
1. **Export**: Click "Export to JSON" to download a backup file
2. **Import**: Use "Import from File" to restore or merge data from a backup
3. **Clear All**: Use "Clear All Data" to reset (with confirmation)

## 🛡️ Privacy & Security

### Local-First Design
- **Your Data Stays Local**: All information stored in your browser's localStorage
- **No Server Communication**: Zero data transmission to external servers
- **No Tracking**: No analytics, cookies, or user tracking
- **Offline Capable**: Works completely offline once loaded

### Security Considerations
- Data is stored unencrypted in browser localStorage
- Anyone with physical access to your device can view the data
- For shared computers, use "Clear All Data" when finished
- Consider using private/incognito browsing mode for temporary usage

## 🔧 Technical Details

### Built With
- **Frontend**: Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Visualization**: D3.js v7 for Sankey diagrams
- **Storage**: Browser localStorage API
- **Design**: CSS Grid, Flexbox, CSS Custom Properties

### Browser Compatibility
- **Chrome**: 60+ ✅
- **Firefox**: 55+ ✅
- **Safari**: 12+ ✅
- **Edge**: 79+ ✅

### File Structure
```
AppTracker/
├── index.html          # Main application file (contains HTML, CSS, JS)
├── README.md           # This documentation
├── LICENSE             # GPL v3 License
└── job_tracker(1).html # Reference design file
```

## 🤝 Contributing

This project was created with assistance from Claude AI. Contributions are welcome!

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development
- **No Build Process**: Edit `index.html` directly
- **Testing**: Open in browser and test functionality
- **Styling**: CSS is embedded in the HTML file

## 📄 License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

### License Summary
- ✅ **Freedom to Use**: Use the software for any purpose
- ✅ **Freedom to Study**: Access and examine the source code
- ✅ **Freedom to Share**: Redistribute copies of the software
- ✅ **Freedom to Improve**: Modify the software and share your improvements
- ⚠️ **Copyleft**: Any modifications must also be licensed under GPL v3

## 🙏 Acknowledgments

- **Claude AI**: For development assistance and code generation
- **D3.js Team**: For the excellent data visualization library
- **Job Seekers**: For inspiring the need for better application tracking tools

## 📞 Support

If you encounter any issues or have suggestions:
1. Check the browser console for error messages
2. Ensure you're using a supported browser
3. Try clearing browser data and reimporting your applications
4. Open an issue on GitHub for bugs or feature requests

---

**Happy Job Hunting!** 🎯

*Track smarter, not harder with the Job Application Tracker.*