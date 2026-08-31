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
│   └── irrigation-portal Exp 4/      # JavaScript Smart Irrigation Web Portal
│       ├── index.html                # Task 1: Soil Moisture & Water Deficit Calculator
│       ├── advisory.html             # Task 2: Irrigation Advisory Engine (Decision Rules)
│       ├── farm-info.html            # Task 3: Sugarcane Farm Object & Pump Status Controller
│       ├── irrigation-table.html     # Task 4: 24-Hour Soil Moisture Sensor Array Analytics
│       ├── registration.html         # Tasks 5 & 6: Farmer Registration & Form Validation
│       ├── style.css                 # Portal Global Stylesheet
│       ├── layout.css                # Flexbox Page Layout Stylesheet
│       └── form.css                  # Form UI Stylesheet
│
└── JavaScript.pptx                   # Reference Presentation
```

---

## 🧪 Experiment 4: JavaScript Logic & Analytics Tasks Overview

1. **Task 1: Soil Moisture & Water Deficit Calculator (`index.html`)**
   - Declares variables (`farmerName`, `plotId`, `currentSoilMoisture`, `requiredSoilMoisture`).
   - Calculates moisture deficit.
   - Outputs status via `document.write()` on load and an interactive calculator with `alert()`.

2. **Task 2: Irrigation Advisory Engine (`advisory.html`)**
   - Applies decision rules:
     - Rain expected $\rightarrow$ *Postpone Irrigation*
     - Soil moisture $< 30\%$ $\rightarrow$ *Irrigation Required Immediately*
     - Soil moisture between $30\%$ and $50\%$ $\rightarrow$ *Monitor Soil Moisture*
     - Soil moisture $> 50\%$ $\rightarrow$ *Irrigation Not Required*

3. **Task 3: Sugarcane Farm Object & Methods (`farm-info.html`)**
   - Object properties: `farmerName`, `plotId`, `cropStage`, `soilMoisture`, `area`, `pumpStatus`.
   - Encapsulates methods: `displayFarmInfo()`, `checkIrrigationRequirement()`, `updatePumpStatus()`.

4. **Task 4: Hourly Sensor Array Analytics (`irrigation-table.html`)**
   - Analyzes a 24-hour soil moisture sensor array.
   - Displays all readings, computes minimum, maximum, average moisture, and counts readings below critical threshold ($< 25\%$).

5. **Tasks 5 & 6: Farmer Registration & Validation Form (`registration.html`)**
   - Validates that no field is empty.
   - Enforces Farmer Name with only alphabets and spaces, Mobile Number of exactly 10 digits, and Plot ID matching pattern **`AGR-1234`**.
   - Validates Soil Moisture ($0\text{--}100\%$), Crop Stage, and Irrigation Date.

---

## 🚀 How to Run Locally

1. Clone or download this repository.
2. To run Experiment 4, open [`Exp 4/irrigation-portal Exp 4/index.html`](Exp%204/irrigation-portal%20Exp%204/index.html) directly in your browser.
