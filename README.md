# Multi-Delivery Access & Data Erasure Portal

A comprehensive web-based portal designed to help delivery platform workers understand deactivation reasons, analyze account status across multiple platforms, and manage data erasure requests.

## 📋 Overview

The **Multi-Delivery Access & Data Erasure Portal** is a professional intake and analysis tool that:

- **Collects detailed client information** through a structured intake form
- **Generates deactivation analysis** based on behavioral and account risk factors
- **Simulates multi-platform tracking** across major delivery services
- **Provides data erasure workflows** for account reset and potential reactivation
- **Offers admin customization** through override panels
- **Supports multiple languages** (English & Spanish)

This portal is designed for users who have been deactivated from delivery platforms like Uber Eats, DoorDash, Instacart, and others, providing insights into the probable reasons for deactivation and pathways to resolution.

## ✨ Features

### Client Intake System
- **Personal Information Collection** - Name, email, phone, location
- **Account Details** - Primary app selection, secondary apps, deactivation date
- **Behavioral Assessment** - Device behavior, delivery patterns, customer complaints
- **Verification Status** - Document issues, background check status
- **Appeal History** - Previous appeals and their outcomes
- **Narrative Context** - Free-form description of events leading to deactivation

### Deactivation Analysis Engine
- **Automated Reason Generation** - Combines multiple risk factors to generate probable deactivation reasons
- **Multi-Factor Assessment** - Evaluates device behavior, delivery patterns, complaints, verification status
- **Appeal Consideration** - Factors in previous appeals and their outcomes
- **Platform-Specific Logic** - Tailors analysis to the selected delivery platform

### Multi-Delivery Live Tracking
- **Real-Time Simulation** - Displays simulated platform events and status updates
- **6 Major Platforms** - Uber Eats, DoorDash, Instacart, Spark Driver, Grubhub, Amazon Flex
- **Dynamic Status Updates** - Rotating platform statuses and activity logs
- **Tab Navigation** - Switch between platforms to view platform-specific insights

### Data Erasure & Reset
- **Shared Verification Layer Cleanup** - Removes identity/document files from cross-platform systems
- **Verification Flag Clearing** - Clears blocked or mismatched verification indicators
- **Reset Module** - Prepares account for potential future verification
- **$75 Processing Fee** - Covers full data erasure and reset workflow

### Admin Controls
- **Override Panel** - Customize generated analysis before sending to clients
- **Status Management** - Update and track processing status
- **Real-Time Adjustments** - Make changes on-the-fly

### Localization
- **English/Spanish Toggle** - Switch between languages for UI elements
- **Responsive Design** - Mobile-friendly interface

## 🚀 Getting Started

### Local Deployment

1. **Clone the repository**
   ```bash
   git clone https://github.com/hacyberglobal/Data-erasure-tool.git
   cd Data-erasure-tool
   ```

2. **Open in browser**
   Simply open `index.html` in your web browser:
   ```bash
   # macOS
   open index.html
   
   # Linux
   xdg-open index.html
   
   # Windows
   start index.html
   ```

3. **No dependencies required** - The portal runs entirely in the browser with vanilla JavaScript

### Web Server Deployment

For production deployment, serve via HTTP/HTTPS:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js http-server
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit: `http://localhost:8000`

## 💻 Usage

### Step 1: Fill Out Intake Form
1. Enter client personal information (name, email, phone)
2. Select location details (country, city)
3. Choose primary affected app and list secondary apps
4. Indicate deactivation date
5. Answer behavioral questions about device usage, delivery patterns, complaints
6. Provide context about document and background check status
7. Describe what happened before deactivation

### Step 2: Generate Analysis
1. Click **"Generate Deactivation Analysis"**
2. The system analyzes the intake data and generates probable deactivation reasons
3. View the generated analysis in the "Generated deactivation analysis" section

### Step 3: Admin Override (Optional)
1. Review the generated text in the **Admin Override Panel**
2. Edit or refine the analysis as needed
3. Click **"Apply Admin Override"** to save custom changes

### Step 4: Live Tracking
1. Switch between platforms using the platform tabs
2. Watch simulated real-time events and status updates
3. Events auto-refresh every 3.5 seconds

### Step 5: Data Erasure Request
1. Review the data erasure scope and implications
2. Proceed with payment processing for the $75 processing fee
3. Receive confirmation when reset has been applied

### Step 6: Language Toggle
1. Click **"ES / EN"** to switch between English and Spanish
2. Portal interface text updates automatically

## 🛠 Technical Details

### Technology Stack
- **Frontend**: Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Architecture**: Client-side single-page application
- **Styling**: Custom responsive CSS with dark theme
- **No external dependencies** - Zero npm/package manager requirements
- **Browser compatibility**: Modern browsers (Chrome, Firefox, Safari, Edge)

### Key Components

#### HTML Structure
- Semantic header with branding
- Responsive input forms with flexible grid layout
- Dynamic content sections with real-time updates
- Admin control panel

#### CSS Features
- **Dark theme** with radial gradients and glassmorphism effects
- **Responsive flexbox** layout for mobile compatibility
- **Custom styling** for inputs, buttons, badges, and status pills
- **Color-coded status** indicators (yellow, green, red)

#### JavaScript Functionality
- **Language toggle** for EN/ES switching
- **Reason generator** combining multiple risk factors
- **Admin override** system for customization
- **Live tracking simulation** with random event generation
- **Real-time updates** every 3.5 seconds

### Data Flow
```
User Input → Intake Form → Analysis Engine → Generated Reason
                                          ↓
                                    Admin Override
                                          ↓
                                    Live Tracking
                                          ↓
                                    Data Erasure Workflow
```

## 📊 Platform Support

### Supported Delivery Platforms
- Uber Eats
- DoorDash
- Instacart
- Spark Driver
- Grubhub
- Amazon Flex
- Shipt
- Roadie
- Gopuff
- Point Pickup
- Lyft Delivery
- Walmart Delivery
- Caviar
- Favor
- SkipTheDishes
- Deliveroo
- JustEat
- Other Platforms

## ⚠️ Important Disclaimer

This portal **simulates deactivation analysis and data-erasure flows**. It does not:
- Replace official decisions from delivery platforms
- Guarantee account reactivation
- Constitute legal advice
- Override platform policies or terms of service

Final decisions regarding account status, reactivation, and data handling remain exclusively with each individual delivery platform.

## 💳 Processing Fee

**$75 Processing Fee** covers:
- Full data-erasure request processing
- Shared-profile cleanup across verification layers
- Activation of reset workflow
- Processing confirmation

Payment processing begins immediately upon completion, with status confirmation provided to the client.

## 🔐 Data Privacy & Security

- **Client data is processed locally** in the browser
- **No external API calls** (except payment processing)
- **No server-side data storage** during simulation
- **Secure session tag** displayed in header
- **Private repository** - Access controlled

## 📧 Support & Contact

For inquiries regarding:
- **Licensing** - Contact Hacyber Global Tech
- **Features** - Submit an issue or pull request
- **Technical support** - Review this README or contact support

## 📄 License

Copyright © 2026 **Hacyber Global Tech**. All Rights Reserved.

This software is the confidential and proprietary information of Hacyber Global Tech. Unauthorized copying, distribution, modification, or use is strictly prohibited.

For licensing inquiries, please contact Hacyber Global Tech.

---

## 🎯 Roadmap

Potential future enhancements:
- Backend integration for persistent data storage
- Payment processing gateway integration
- Email confirmation system
- Advanced analytics dashboard
- API endpoints for platform integration
- Database for case management
- User authentication system
- Detailed case tracking and reporting

## 👥 Contributing

Contributions welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request with detailed descriptions

## 🙏 Acknowledgments

Built with attention to detail for delivery platform professionals seeking clarity on account status and resolution pathways.

---

**Status**: Active & Maintained  
**Last Updated**: June 2026  
**Version**: 1.0.0
