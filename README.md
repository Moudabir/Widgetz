# Idea Capture Widget

A lightweight, self-contained HTML widget for capturing and organizing ideas, tasks, notes, and reminders. Built with vanilla JavaScript and CSS, this widget provides a clean, intuitive interface for personal productivity and idea management.

## Features

### 📝 Core Functionality
- **Quick Capture**: Add ideas, tasks, notes, and reminders instantly
- **Categorization**: Organize items into four categories: Tasks, Ideas, Notes, and Reminders
- **Persistent Storage**: All data is saved locally in your browser's localStorage
- **Real-time Stats**: View counts for total items and each category

### 🎯 Organization Tools
- **Category Filtering**: Filter items by category or view all at once
- **Visual Categories**: Color-coded badges for easy identification
- **Timestamps**: Automatic date tracking for each item
- **Delete Functionality**: Remove individual items or clear all data

### 📤 Export Options
- **JSON Export**: Copy structured data to clipboard for backup or integration
- **CSV Export**: Download data as a CSV file for spreadsheet analysis
- **Data Portability**: Easy export for use in other applications

## Usage

### Getting Started
1. Open `idea-capture-widget.html` in any modern web browser
2. Start adding items using the input field and category selector
3. Use filters to organize your view
4. Export data when needed

### Adding Items
- Type your idea/task/note/reminder in the text field
- Select the appropriate category from the dropdown
- Click "Add" or press Enter to save

### Filtering
- Click filter buttons to show only items from specific categories
- Use "All" to view everything

### Exporting Data
- **Copy JSON**: Click to copy all data to clipboard
- **Export CSV**: Download a CSV file with your data
- **Clear All**: Remove all items (with confirmation)

## Technical Details

### Technologies Used
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript**: No external dependencies
- **localStorage API**: Client-side data persistence

### Browser Support
- Modern browsers with ES6+ support
- localStorage enabled
- Clipboard API for JSON export

### Data Structure
Items are stored as JSON objects with the following structure:
```json
{
  "text": "Your idea or task",
  "category": "task|idea|note|reminder",
  "timestamp": "2024-01-01T12:00:00.000Z"
}
```

### File Size
- Complete widget: ~15KB (minified)
- No external dependencies or CDN requirements
- Self-contained and portable

## Installation

### Option 1: Direct File
1. Download `idea-capture-widget.html`
2. Open in any web browser
3. Data persists locally in browser storage

### Option 2: Web Integration
- Embed the HTML file in any web application
- Host on any static web server
- No server-side requirements

## Customization

The widget is built with standard web technologies and can be customized by:
- Modifying CSS styles for branding
- Extending JavaScript for additional features
- Integrating with external APIs for cloud sync

## Privacy & Security

- All data stored locally in browser
- No data transmitted to external servers
- No tracking or analytics
- Complete user control over data

## License

This project is open source and available under standard open source licenses.
