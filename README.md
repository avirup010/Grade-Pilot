
# ✈️ GradePilot  
### Quick Grades, Instant Results  

GradePilot is a streamlined GPA calculator tailored for students, built into a single HTML file. Following SRM Institute of Science and Technology (SRMIST)’s grading system, it delivers fast, accurate results with a polished, animated interface—no setup needed, just efficiency.

---

## Overview  
GradePilot is a self-contained web tool that computes your Grade Point Average (GPA) based on SRMIST’s 10-point grading scale. Input courses via grades or marks, manage your list, and get instant results in a responsive, modern design.

---

## Key Features  
- **SRMIST Grading**: Adheres to SRMIST’s system—O (10) to F/Ab (0)—with marks mapped to grades (e.g., 91-100 = 10).  
- **Flexible Input**: Choose direct grade selection (O to F) or marks entry (0-100), auto-converted to SRMIST points.  
- **Course Management**: Add, delete, or clear courses with smooth transitions.  
- **Real-Time Calculation**: Computes GPA as (grade points × credits) ÷ total credits, displayed with a counting animation.  
- **Visual Design**: Card-based layouts, subtle shadows, and animations for a standout experience.  
- **Cross-Device**: Fully responsive for desktop or mobile use.  

---

## Technical Breakdown  
All components are packed into one `.html` file:  
- **HTML**: Structures the interface with forms, tabs, and result displays.  
- **CSS**: Embedded in `<style>`, offering clean styling, flexbox layouts, and animations (e.g., `slideUp`, `pop`).  
- **JavaScript**: Embedded in `<script>`, driving interactivity—event handling, DOM updates, and SRMIST-specific calculations.  

Notable mechanics:  
- **Input Modes**: Toggles between grade and marks inputs, validated for SRMIST compliance.  
- **Grading System**: Reflects SRMIST standards—O (91-100), A+ (81-90), down to F (<40), with a reference table included.  
- **Animations**: Combines CSS keyframes and JavaScript for fluid feedback like button pops and course removals.  

---

## Getting Started  
1. Download `gradepilot.html` from this repository.  
2. Open it in any modern web browser.  
3. Add your courses and calculate your GPA per SRMIST’s system.  

---

## Why GradePilot?  
- **SRMIST-Aligned**: Perfect for SRMIST students, mirroring the institute’s official grading structure.  
- **Portable**: Single-file design with no dependencies—just download and use.  
- **Professional Finish**: Clean UI, precise calculations, and animations elevate it beyond a basic tool.  
- **User-Centric**: Supports Enter key inputs, visual error cues, and a grading table for clarity.  

---

## Code Insights  
- **CSS**: Modern flexbox and media queries ensure responsiveness, with custom keyframes for animations.  
- **JavaScript**: Powers the logic—course rendering, SRMIST GPA math, and animation triggers—optimized for accuracy.  
- **HTML**: Lean structure with semantic elements, including SRMIST’s grading table for reference.  

Dive into the source—it’s compact, well-organized, and easy to tweak.

---

## Usage  
Clone or download this repo to start using GradePilot. It’s crafted for SRMIST students and educators who need a quick, stylish way to track CGPA.  

*Developed by Avi*
