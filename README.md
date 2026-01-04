# Canadian Tax Calculator 

A comprehensive web-based tax calculator for Canadian federal and provincial income taxes. Built with vanilla HTML, CSS, and JavaScript for accuracy, performance, and ease of use.

## 🚀 Live Demo

**👉 [Try the Calculator Live](https://sudip-sasquash0x01.github.io/Canadian-Tax-Calculator/)**

## Overview

This calculator provides detailed tax calculations for all 13 Canadian provinces and territories using official 2024 tax brackets and rates. It includes advanced features for RRSP optimization, investment income planning, and family benefit calculations.

## Features

### Core Tax Calculations
- Federal and provincial tax calculations for all provinces and territories
- Accurate 2024 tax brackets and rates from Canada Revenue Agency
- CPP and EI contribution calculations including CPP2 enhancement
- Real-time tax calculations with instant updates

### Income Types Supported
- Employment income (T4, tips, commissions, bonuses)
- Self-employment income with business expense deductions
- Investment income (dividends, capital gains, interest)
- Pension income and RRSP withdrawals
- Other income sources (EI benefits, etc.)

### Deductions and Credits
- RRSP contribution optimization (2024 limit: $31,560)
- Medical expense credit with 3% threshold calculation
- Charitable donation credit with tiered rates
- Tuition and education credits
- Common tax credits and deductions

### Advanced Features
- TFSA contribution room tracking (2024 limit: $7,000)
- Canada Child Benefit calculator with income testing
- Pension income splitting for couples
- Multi-scenario comparison tools
- Tax planning and optimization suggestions
- Data persistence across browser sessions

### Visual Tools
- Tax bracket visualization charts
- Marginal vs average tax rate displays
- Interactive forms with real-time validation
- Responsive design for mobile and desktop

## Technical Implementation

### Architecture
- Single-page application using vanilla JavaScript
- Modular code structure with separate calculation functions
- Object-oriented data management
- CSS Grid and Flexbox for responsive layouts

### Data Accuracy
- 2024 federal tax brackets: 15%, 20.5%, 26%, 29%, 33%
- Complete provincial tax data for all 13 provinces/territories
- Current CPP/EI rates and maximums
- Official CRA basic personal amounts and thresholds

### Browser Compatibility
- Modern browsers supporting ES6+ features
- No external dependencies or frameworks required
- Progressive enhancement for optimal performance

## Installation and Usage

### Quick Start
1. Download all files to your web server
2. Open `index.html` in a modern web browser
3. Enter your income and tax information
4. View calculated results and optimization suggestions

### Local Development
1. Clone or download the repository
2. Open `index.html` in a web browser (no build process required)

### Deployment
- Upload all files to any web hosting service
- Ensure proper MIME types for CSS and JavaScript files
- No server-side processing required

## Input Validation

The calculator includes comprehensive validation:
- Numeric inputs with min/max constraints
- Real-time feedback on invalid entries
- Form validation before calculations
- Error handling for edge cases

## Data Storage

- Browser-based storage for user scenarios
- No personal data transmitted to external servers
- Automatic saving of calculation progress
- Export functionality for backup purposes

## Accuracy and Limitations

### Accurate Calculations
- Federal and provincial tax brackets for 2024
- CPP and EI rates as published by CRA
- Basic personal amounts and common credits
- Investment income tax rules (dividend gross-up, capital gains)

### Limitations
- Simplified calculations for demonstration purposes
- Does not replace professional tax advice
- May not cover all tax situations or credits
- Tax laws subject to change

### Disclaimer
This calculator provides estimates based on 2024 tax rules. Results should not be considered as professional tax advice. For complex tax situations or official calculations, consult a qualified tax professional or the Canada Revenue Agency.

## Browser Requirements

- JavaScript enabled
- Modern browser (Chrome 70+, Firefox 65+, Safari 12+, Edge 79+)
- Local storage support for data persistence
- No plugins or extensions required

### Adding Features
- Functions organized in separate modules
- Clear separation between calculation logic and UI
- Event-driven architecture for easy extension

## Performance

- Lightweight vanilla JavaScript implementation
- No external library dependencies
- Optimized for fast loading and responsive interaction
- Efficient calculation algorithms
- Minimal DOM manipulation

## Security

- Client-side only processing
- No data transmission to external servers
- Input sanitization and validation
- Safe evaluation of user inputs

## Support

For technical issues or questions about tax calculations:
- Review CRA official documentation
- Consult with qualified tax professionals
- Check browser console for error messages

## License

This project is provided for educational and demonstration purposes. Tax calculation accuracy is not guaranteed. Users should verify results with official CRA resources or tax professionals.