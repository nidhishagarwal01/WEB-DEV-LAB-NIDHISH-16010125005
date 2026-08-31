# Web Development Laboratory - Practical Assignments

**Student Name:** Nidhish Agarwal  
**Roll No:** 16010125005  
**Course:** Web Development Laboratory (316U01L306)  
**Batch:** A1 | Semester: III  

---

## 📂 Repository Structure

```text
├── Exp 1/
│   ├── Exp 1 Web Dev 16010125005 Nidhish.docx
│   ├── Exp 1 Web Dev 16010125005 Nidhish.pdf
│   └── irrigation-portal Exp 1/      # HTML5 Front-End Implementation
│       ├── index.html                # Task 1: Homepage Structure & Semantic Tags
│       ├── farm-info.html            # Task 2: Farm Information (Lists & Text Formatting)
│       ├── advisory.html             # Task 3: Today's Irrigation Advisory
│       ├── gallery.html              # Task 4: Farm Photo Gallery (Figure/Figcaption)
│       ├── plot-map.html             # Task 5: Farm Plot Navigation (Image Map)
│       ├── irrigation-table.html     # Task 6: Soil Moisture & Sensor Data Table
│       ├── registration.html         # Task 7: Farmer Registration Form (HTML5 Validation)
│       ├── weather.html              # Task 8: Weather Forecast & Location (IFrames)
│       ├── media.html                # Task 9: Awareness Media (Video, Audio & Script)
│       ├── images/                   # Asset images for crop, sensors, and map
│       ├── audio/                    # Audio assets
│       └── media/                    # Video assets
│
├── Exp 2/
│   ├── Nidhish Agarwal Exp 2.docx
│   └── irrigation-portal Exp 2/      # CSS3 Enhanced Web Portal Implementation
│       ├── index.html                # Task 1, 2, 4, 9: Inline CSS, Nav, Sidebar & Layout
│       ├── farm-info.html            # Task 5: Sensor Cards using CSS Box Model
│       ├── advisory.html             # Task 10: Highlighting & Glowing Keyframe Animations
│       ├── gallery.html              # Task 6: Gallery Grid & Image Hover Zoom Effects
│       ├── irrigation-table.html     # Task 7: Table Styling with Zebra Striping
│       ├── registration.html         # Task 8: Form UI Styling & Focus Effects
│       ├── weather.html              # Weather Forecast Module
│       ├── plot-map.html             # Plot Map Module
│       ├── media.html                # Multimedia Module
│       ├── style.css                 # Task 3: Site-wide Theme & Reusable Component Styles
│       ├── layout.css                # Task 9: Flexbox 2-Column Responsive Layout
│       ├── table.css                 # Task 7: External Table Stylesheet
│       ├── form.css                  # Task 8: External Form Stylesheet
│       ├── images/                   # Asset images
│       ├── audio/                    # Audio assets
│       └── media/                    # Video assets
│
├── Exp 3/                            # JavaScript Basics (Classroom Practicals)
│   ├── 1_simple.html                 # Program 1: Simple JavaScript (DOM Manipulation)
│   ├── 2_functions.html              # Program 2: Functions & Events (onclick, onmouseover)
│   └── 3_form_validation.html        # Program 3: Form Validation
│
├── Exp 4/                            # Advanced Client-Side JavaScript Logic & Analytics
│   ├── JavaScript-tasks-WDL.docx     # Experiment 4 Task Requirements Manual
│   └── irrigation-portal Exp 4/      # Full-Stack JavaScript Smart Irrigation Portal
│       ├── index.html                # Experiment 4 Hub & Module Directory
│       ├── task1_calculator.html     # Task 1: Soil Moisture & Water Deficit Calculator
│       ├── task2_advisory.html       # Task 2: Irrigation Recommendation Engine (Decision Rules)
│       ├── task3_farm_object.html    # Task 3: Sugarcane Farm JavaScript Object & Methods
│       ├── task4_sensor_array.html   # Task 4: 24-Hour Soil Sensor Array Analytics
│       ├── task5_validation.html     # Task 5: Farmer Name, Mobile & Plot ID Validator
│       ├── task6_registration_form.html # Task 6: Interactive Registration & Advisory Request Form
│       ├── farm-info.html            # Farm Information Dashboard
│       ├── gallery.html              # Farm Photo Gallery
│       ├── plot-map.html             # Farm Plot Map
│       ├── irrigation-table.html     # Sensor Data Table
│       ├── weather.html              # Weather Forecast Module
│       ├── media.html                # Multimedia Awareness Module
│       ├── style.css                 # Global Theme Stylesheet
│       ├── layout.css                # Flexbox Page Layout Stylesheet
│       ├── form.css                  # Form UI Stylesheet
│       └── table.css                 # Table UI Stylesheet
│
└── JavaScript.pptx                   # Reference Presentation
```

---

## 🧪 Experiments Overview

### 🌾 Experiment 1: HTML5 Front-End Development
- Semantic document structure (`<header>`, `<nav>`, `<section>`, `<article>`, `<aside>`, `<footer>`)
- Lists (`<ol>`, `<ul>`, `<dl>`) and text formatting tags
- Accessible image maps (`<map>`, `<area>`) for farm plot navigation
- Data tables (`<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, `rowspan`, `colspan`)
- HTML5 Form input validation and embedded widgets (`<iframe>`, `<video>`, `<audio>`)

### 🎨 Experiment 2: CSS3 Styling & Responsive Design
- **Inline, Internal, and External CSS** styling techniques
- **CSS Box Model & Flexbox** for card layouts and multi-column web design
- **Transitions & Hover Effects** (`transform: scale()`, translateY)
- **Table Zebra-Striping & Form Styling** with glowing focus rings
- **Keyframe Animations** (`@keyframes glow`) for advisory alerts

### ⚡ Experiment 3: Client-Side JavaScript Basics
- Core syntax, variables, operators, conditions, loops, and DOM manipulation
- Functions with event handlers (`onclick`, `onmouseover`, `onmouseout`)
- Form validation with real-time feedback

### 🌾 Experiment 4: JavaScript Logic, Analytics & Verification for Smart Irrigation
Full integration of JavaScript modules into the Smart Irrigation Advisory Portal:
1. **Task 1 (`task1_calculator.html`)**: Soil Moisture & Water Requirement Calculator (evaluating moisture deficit with `alert()` and `document.write()`).
2. **Task 2 (`task2_advisory.html`)**: Irrigation Recommendation Engine using decision rules for soil moisture, rainfall forecasts, and crop growth stages.
3. **Task 3 (`task3_farm_object.html`)**: Sugarcane Farm Object encapsulation with properties (`farmerName`, `plotId`, `cropStage`, `soilMoisture`, `area`, `pumpStatus`) and methods (`displayFarmInfo()`, `checkIrrigationRequirement()`, `updatePumpStatus()`).
4. **Task 4 (`task4_sensor_array.html`)**: Hourly Soil Sensor Array Analytics computing Minimum, Maximum, Average moisture, and critical limit count (< 25%).
5. **Task 5 (`task5_validation.html`)**: Parameter validation engine for Farmer Name (alphabets/spaces), 10-digit Mobile Number, and Plot ID (`AGR-1234`).
6. **Task 6 (`task6_registration_form.html`)**: Interactive Farmer Registration and Advisory Request Form with client-side field validation.

---

## 🚀 How to Run Locally

1. Clone or download this repository.
2. Open any `.html` file directly in your web browser.
3. To view the complete portal for Experiment 4, open [`Exp 4/irrigation-portal Exp 4/index.html`](Exp%204/irrigation-portal%20Exp%204/index.html).
