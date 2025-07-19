# Enhanced Case Timeline Scraper v2.0 <img alt="Static Badge" src="https://img.shields.io/badge/Status-IN_DEVELOPMENT-red">


## Overview

The Enhanced Case Timeline Scraper v2.0 is a powerful web application designed to help legal professionals analyze chronological case data and identify potential rights violations. This improved version includes advanced features for better case management and analysis.

## Key Features

### 🎯 Core Functionality
- **Interactive Timeline Visualization** - Horizontal scrollable timeline with color-coded events
- **Rights Violation Analysis** - AI-powered detection of potential procedural violations
- **Case Type Detection** - Automatic identification of criminal, civil, family, or probate cases
- **Statistical Dashboard** - Comprehensive metrics and data visualization

### 🔧 Advanced Features
- **Customizable Deadline Rules** - Set jurisdiction-specific deadlines for omnibus, discovery, and trial
- **Event Filtering & Search** - Filter by event type and search by keywords
- **Event Annotations** - Add notes and comments to specific events
- **Multiple Export Options** - Export data as JSON, CSV, or PDF
- **File Upload Support** - Import existing JSON/CSV timeline data
- **Timeline Controls** - Zoom in/out and pan through long timelines
- **Accessibility Features** - ARIA labels and keyboard navigation support

### 📊 Data Visualization
- **Event Type Distribution Chart** - Doughnut chart showing case activity breakdown
- **Case Activity Timeline** - Line chart displaying events over time
- **Deadline Visualization** - Color-coded bars for omnibus (green), discovery (yellow), and trial (red) deadlines
- **Color-coded Events** - Visual indicators for different event types

## How to Use

### Method 1: Manual Data Entry
1. Copy the chronological case summary from MyCase
2. Paste it into the text area
3. Click "Parse Manual Data"

### Method 2: File Upload
1. Prepare a JSON or CSV file with timeline data
2. Use the file upload input
3. The app will automatically parse and display the data

### Method 3: Sample Data
1. Click "Load Sample Case" to see the app in action
2. Explore all features with realistic demo data

## Configuration Options

### Deadline Settings
- **Omnibus Days**: Default 70 days from filing
- **Discovery Days**: Default 120 days from filing  
- **Trial Days**: Default 180 days from filing
- **Case Type**: Auto-detect or manually select (Criminal, Civil, Family, Probate)

### Event Filtering
- Filter by event type (Filing, Hearing, Motion, Service, Discovery, Trial, Judgment)
- Search events by keyword
- Clear filters to show all events

## Rights Violation Analysis

The app automatically analyzes cases for potential rights violations:

### Violation Types
- **Omnibus Hearing Violations** - Missing or delayed omnibus hearings
- **Discovery Deadline Violations** - Insufficient discovery activity
- **Trial Deadline Violations** - Delayed trials (especially critical for criminal cases)

### Severity Levels
- **High**: Critical violations (e.g., speedy trial violations in criminal cases)
- **Medium**: Significant procedural delays
- **Low**: Minor timeline deviations

## Technical Features

### Libraries Used
- **Chart.js** - Data visualization and charting
- **jsPDF** - PDF export functionality
- **Tailwind CSS** - Modern, responsive styling

### Browser Compatibility
- Modern browsers with ES6+ support
- Responsive design for desktop and mobile
- Keyboard navigation support

### Data Format
The app expects chronological case data in this format:
```
07/15/2024
Case Opened as a New Filing
COMPLAINT
For Party: John Doe vs. ABC Corporation

07/16/2024
Appearance Filed
APPEARANCE
For Party: ABC Corporation
```

## Export Options

### JSON Export
- Complete timeline data with analysis results
- Includes violation analysis and deadline calculations
- Preserves all event notes and annotations

### CSV Export
- Tabular format suitable for spreadsheet applications
- Includes all event details and notes
- Compatible with Excel and Google Sheets

### PDF Export
- Professional report format
- Includes timeline summary and violation analysis
- Suitable for client reports and court filings

## Accessibility Features

- **ARIA Labels** - Screen reader support for all interactive elements
- **Keyboard Navigation** - Full keyboard access to timeline events
- **High Contrast** - Clear visual indicators and readable text
- **Focus Management** - Proper focus handling for interactive elements

## Best Practices

### For Legal Professionals
1. **Customize Deadlines** - Set jurisdiction-specific rules before analysis
2. **Add Notes** - Document important observations for each event
3. **Export Regularly** - Save analysis results for case files
4. **Review Violations** - Pay special attention to high-severity violations

### For Case Management
1. **Use Filtering** - Focus on specific event types when needed
2. **Timeline Navigation** - Use zoom controls for detailed analysis
3. **Statistical Review** - Check dashboard metrics for case overview
4. **Regular Updates** - Re-analyze as new events are added

## Troubleshooting

### Common Issues
- **CORS Errors**: Use manual data entry instead of URL scraping
- **Parse Errors**: Ensure data follows the expected MyCase format
- **Export Issues**: Check browser download settings
- **Display Problems**: Ensure JavaScript is enabled

### Data Quality Tips
- Verify date formats (MM/DD/YYYY)
- Check for complete event descriptions
- Ensure party information is included
- Remove extraneous formatting before pasting

## Future Enhancements

Potential improvements for future versions:
- Integration with legal case management systems
- Advanced AI-powered violation detection
- Multi-jurisdiction rule sets
- Collaborative case analysis features
- Real-time case monitoring

## Support

For technical issues or feature requests, please refer to the application's built-in help system or contact your system administrator.

---

**Enhanced Case Timeline Scraper v2.0** - Empowering legal professionals with advanced case analysis tools.

