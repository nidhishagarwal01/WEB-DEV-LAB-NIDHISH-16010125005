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
├── Exp 3/                            # JavaScript Programs (as per Teacher's Presentation)
│   ├── index.html                    # Experiment 3 Navigation Dashboard Hub
│   ├── 1_simple.html                 # Program 1: Simple JavaScript (Variables, Operators, Control & Loops)
│   ├── 2_functions.html              # Program 2: Functions, Objects, Constructor, Events & DOM
│   └── 3_form_validation.html        # Program 3: Interactive Form Validation & Error Handling
│
└── JavaScript.pptx                   # Reference Presentation
```

---

## 🧪 Experiments Overview

### 🌾 Experiment 1: HTML5 Front-End Development
Demonstrates core HTML5 concepts:
- Semantic document structure (`<header>`, `<nav>`, `<section>`, `<article>`, `<aside>`, `<footer>`)
- Lists (`<ol>`, `<ul>`, `<dl>`) and formatting tags (`<b>`, `<i>`, `<mark>`, `<strong>`, `<em>`)
- Accessible image maps (`<map>`, `<area>`) for farm plot navigation
- Data tables (`<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, `rowspan`, `colspan`)
- HTML5 Form input validation (`pattern`, `required`, `autofocus`, `type="date"`, etc.)
- Embedded external widgets (`<iframe>`) and multimedia (`<video>`, `<audio>`)

### 🎨 Experiment 2: CSS3 Styling & Responsive Design
Demonstrates progressive CSS3 features:
- **Inline, Internal, and External CSS** styling techniques
- **CSS Box Model & Flexbox** for modern card layouts and multi-column web design
- **CSS Grid & Transitions** (`transform: scale()`) for image gallery zoom effects
- **Table & Form Enhancement** with zebra-striping, custom focus rings, and gradient buttons
- **Animations & Effects** (`@keyframes glow`, text/box shadows) for critical advisory highlights
- **Responsive Web Design** via media queries (`@media (max-width: 700px)`) for mobile compatibility

### ⚡ Experiment 3: Client-Side JavaScript Programming
Implements 3 comprehensive programs strictly adhering to the lecture presentation topics:
1. **Program 1 (`1_simple.html`) — Simple JavaScript Program**:
   - Variables (`var`), Data Types (String, Number, Boolean, Array)
   - Arithmetic, comparison, and logical operators
   - Conditional structures (`if-else`, `switch` on Date)
   - Loops (`for`, `while`)
   - DOM manipulation (`innerHTML`, style modification, hide/show toggle)
2. **Program 2 (`2_functions.html`) — Use of Functions & Objects**:
   - Parameterized functions with return values
   - Object literals with methods
   - Constructor Functions with `this` keyword & `new` instantiation
   - Event Handling (`onclick`, `onmouseover`, `onmouseout`, `onchange`)
   - DOM querying via `getElementsByName()` and `getElementsByTagName()`
3. **Program 3 (`3_form_validation.html`) — Form & Validation**:
   - Event interception using `onsubmit="return validateForm()"`
   - Client-side validation: Name alphabetic check, 10-digit mobile number, regex email format, Plot ID code formatting, and numeric bounds (0-100% moisture)
   - Dynamic error spans with red input borders and green valid state feedback
   - Exception Handling (`try ... catch`)

---

## 🚀 How to Run Locally

1. Clone or download this repository.
2. Open any `.html` file in your preferred web browser (Chrome, Firefox, Safari, Edge).
3. To view Experiment 3, launch [`Exp 3/index.html`](Exp%203/index.html) to navigate between all three JavaScript programs.
