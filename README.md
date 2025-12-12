CaffeineForge Pro ☕

Smart Caffeine Response Calculator & Visualization Tool

A mobile-first, interactive web application that models caffeine's physiological effects using real pharmacokinetic principles. Built for science communication and personalized caffeine optimization.

🚀 Live Demo

[Hosted Link Here] • [Direct GitHub Pages Link]

✨ Features

📊 Interactive Modeling

· Dose-response curve visualization with three-phase model (increasing → diminishing → negative returns)
· Personalized physiology inputs (body weight, metabolism type, tolerance)
· Real-time parameter adjustments with immediate visual feedback
· Advanced curve controls (steepness, saturation point, negative slope)

📱 Mobile-Optimized UX

· Thumb-friendly sliders with haptic feedback simulation
· Tab-based navigation for complex features
· Collapsible sections to manage screen real estate
· Native share API integration

🧪 Science-Based Calculations

· CYP1A2 metabolism variants (slow/normal/fast metabolizer modeling)
· Half-life decay simulations (3-8 hour range based on genetics)
· Tolerance buildup modeling over days/weeks
· Risk assessment engine (anxiety, sleep disruption, heart rate, tolerance)

📈 Practical Tools

· Drink tracker & timeline - Log consumption with real-time metabolism simulation
· Dosage calculator - Compare intake against personalized safe limits
· Export functionality - CSV data, PNG charts, full text reports
· Educational content - Built-in caffeine science guide

🛠️ Technology Stack

· Frontend: Pure HTML5, CSS3, Vanilla JavaScript
· Visualization: Plotly.js for interactive charts
· Icons: Font Awesome 6
· Design: Mobile-first responsive design with CSS Grid/Flexbox
· No build tools required - runs directly in modern browsers

📁 Project Structure

```
caffeine-forge-mobile-pro.html
├── Header & Navigation
├── Tab System (4 main sections)
│   ├── Calculator (main modeling interface)
│   ├── Drinks (tracker & timeline)
│   ├── Insights (risk assessment & recommendations)
│   └── Education (science content)
├── Interactive Controls
│   ├── Touch-optimized sliders
│   ├── Toggle switches
│   ├── Radio groups
│   └── Card-based UI
└── Visualization Components
    ├── Plotly.js charts
    ├── Progress bars
    ├── Metric cards
    └── Timeline visualization
```

🧬 Scientific Foundation

The model incorporates:

· Adenosine receptor antagonism mechanism
· CYP1A2 genetic polymorphism effects on metabolism
· Three-phase response curve based on pharmacological principles
· FDA/medical guideline safety limits (400mg daily maximum)
· Pregnancy/nursing adjusted recommendations (200mg limit)

🚦 Quick Start

1. Download the HTML file
2. Open in any modern web browser
3. No installation required

Or deploy instantly:

· Drag & drop to Netlify Drop
· Upload to GitHub Pages
· Host on any static web server

🔧 Development

Local Development

```bash
# Just open the HTML file!
open caffeine-forge-mobile-pro.html
```

Customization

· Edit CSS variables in :root section to change colors
· Modify drinkPresets array in JavaScript to add custom beverages
· Adjust metabolismProfiles for different half-life modeling
· Customize recommendations in generateRecommendations() function

Browser Support

· Chrome 60+ ✅
· Firefox 55+ ✅
· Safari 12+ ✅
· Edge 79+ ✅
· Mobile Safari/Chrome ✅

📚 Usage Scenarios

For Individuals

· Find your personal caffeine sweet spot
· Track daily consumption
· Understand genetic metabolism differences
· Plan caffeine intake around sleep schedules

For Educators

· Demonstrate dose-response principles
· Visualize pharmacokinetic concepts
· Show real-time effects of parameter changes

For Researchers

· Prototype compound-effect visualization
· Test modeling approaches
· Educational tool for patient communication

🎯 Key Algorithms

Dose-Response Calculation

```javascript
// Three-phase model:
// 1. Growth phase (c <= saturation): Sigmoid growth
// 2. Diminishing returns (c > saturation): Gradual decline
// 3. Negative returns (c >> saturation): Anxiety/jitters override
```

Metabolism Simulation

```javascript
// Half-life decay: remaining = initial * (0.5)^(hours/halfLife)
// Genetic variants: CYP1A2 slow/normal/fast metabolizers
// Adjustments: pregnancy, body mass, tolerance
```

Risk Assessment

```javascript
// Four risk factors calculated:
// 1. Anxiety/Jitters (exponential above saturation)
// 2. Sleep Disruption (linear with remaining caffeine at bedtime)
// 3. Heart Rate (sigmoid function of dose/weight ratio)
// 4. Tolerance Buildup (logarithmic over time)
```

📱 Mobile Optimizations

· Touch targets: Minimum 44×44px for all interactive elements
· Gesture support: Swipe-friendly tab navigation
· Performance: 60fps animations, optimized redraws
· Accessibility: ARIA labels, keyboard navigation, reduced motion support
· Offline capable: Works without internet after initial load

🔄 Export Options

1. PNG Charts - High-resolution graphs
2. CSV Data - Raw response curve data with parameters
3. Text Reports - Personalized recommendations with risk assessment
4. Share Links - Native sharing to social/media apps

🤝 Contributing

This is a demonstration project. For educational modifications:

1. Fork the repository
2. Make improvements (consider adding PWA capabilities, data persistence, or API integration)
3. Submit a pull request

📄 License

Educational Use - Built for science communication demonstration.

Disclaimer: This tool provides estimates based on published research. It is not medical advice. Consult healthcare professionals for personal health decisions.

🙏 Acknowledgments

· Plotly.js for beautiful, interactive charts
· Font Awesome for icons
· Caffeine research community for pharmacokinetic data
· Inspired by conversations with pharmaceutical scientists

📈 Future Enhancements (Potential)

· PWA installation with offline data persistence
· Integration with health APIs (Apple Health, Google Fit)
· Machine learning for personalized curve fitting
· Multi-compound interaction modeling
· Clinical validation studies

---

Made with ❤️ for science communication. Brew responsibly. ☕
