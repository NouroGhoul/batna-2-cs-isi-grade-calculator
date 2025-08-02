# Batna2 University Grade Calculator - CS ISI Master 1

![Calculator Preview](screenshots/preview.png)

## Overview

This web application calculates semester averages for CS/ISI Master 1 students at Batna 2 University according to the official grading system defined by the Algerian Ministry of Higher Education.

## Features

- 🎓 Calculate averages for both S1 and S2 semesters
- 📊 Detailed grade breakdown for each module
- ✅ Pass/Fail indication with visual feedback
- 📱 Responsive design works on all devices
- ⚡ Real-time calculations with instant results
- 📈 Weighted average based on module coefficients

## How to Use

1. Select your semester (S1 or S2)
2. Enter your grades for each module component (Exam, TD, TP)
3. Click "Calculate Average"
4. View your final average and module-by-module results

## Calculation Methodology

The calculator follows the official grading system as defined in the Algerian Ministry of Higher Education document:

[Master ISI Program - Algerian Ministry of Higher Education](https://cs.univ-batna2.dz/sites/default/files/web/files/master_isi_final_mesrs_apres_recours.pdf)

### Grading Formula

The calculation uses weighted averages based on module coefficients:

```
Final Average = Σ (Module Grade × Coefficient) / Total Coefficients
```

### Module Components

Each module grade is calculated based on its components:

- **Modules with Exam + TD + TP**  
  `(Exam × 0.6) + (TD × 0.2) + (TP × 0.2)`
  
- **Modules with Exam + TD**  
  `(Exam × 0.6) + (TD × 0.4)`
  
- **Modules with Exam + TP**  
  `(Exam × 0.6) + (TP × 0.4)`
  
- **Modules with only Exam**  
  `Exam × 1.0`


## Technical Implementation

The calculator is implemented as a single HTML file with embedded CSS and JavaScript:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Meta tags and title -->
    <style>
        /* All CSS styles */
    </style>
</head>
<body>
    <!-- UI structure -->
    <script>
        // JavaScript functionality
    </script>
</body>
</html>
```

### Key Components

1. **Semester Selection** - Choose between S1 and S2 modules
2. **Dynamic Module Loading** - Modules load based on semester selection
3. **Grade Validation** - Ensures all inputs are between 0-20
4. **Weighted Calculation** - Computes final average based on coefficients
5. **Visual Feedback** - Color-coded pass/fail indicators

## License

This project is licensed under the MIT License:

```
Copyright (c) 2025 [https://github.com/NouroGhoul]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## How to Run

Simply open the `BATNA2_ISI_M1_CALC.html` file in any modern web browser. No installation or server required.

## Contribution

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.