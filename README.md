### 📄 Tamil Nadu Government School Marksheet Generator

The Tamil Nadu Government School Marksheet Generator is a client-side web application developed using HTML, CSS, and JavaScript that dynamically compiles and simulates official school-level academic statements of marks. The application accommodates structural variations across Classes 1–12, handling complex multi-stream profiles for higher secondary students and enforcing automated board evaluations smoothly on a single page.

The interface is carefully modeled after an authentic government layout, complete with institutional typography, custom SVG state emblems, structured tables, and security watermarks to achieve a realistic academic presentation.

---

### 🎯 Objectives of the Project

* To design a professional, standard-compliant academic certificate interface.
* To implement real-time input validations for student grades and marks.
* To automatically process class-specific performance metrics and higher education thresholds.
* To demonstrate robust JavaScript DOM manipulation, structural array mapping, and state control.
* To enhance modular front-end design skills using clean, responsive CSS grid configurations.

---

### 🧩 Key Features

* **Multi-Class Layout Architecture**: Dynamically remaps required fields and subject arrays depending on the selected standard (Primary up to High Secondary).
* **Higher Secondary Stream Routing**: Supports discrete data sets for *Bio-Maths, CS-Maths,* and various *Commerce* groupings.
* **Intelligent Input Filtering**: Live field monitoring restricts inputs between $0$ and $100$, providing real-time green/red border feedback.
* **Automated Calculations Engine**: Instantly computes performance factors:
* Cumulative Total Marks
* Final Percentage Profile
* Subject-by-Subject Grade Allocation (`A+` through `E`)
* Global Pass/Fail Verification (Minimum 35 marks per subject requirement)


* **Conditional Class 12 Cut-Off Matrix**: Automatically processes localized Engineering (out of 200) or Arts/Commerce (out of 400) cut-offs **only if** the student passes all papers.
* **Dynamic Reappear Banner**: If a Class 12 student fails any subject, the system safely suppresses the cut-off panel and alerts the user that the candidate must reappear.
* **Print Layout Optimization**: Built-in styling controls isolate the main marksheet container and format it seamlessly for clean physical printing or PDF downloads.

---

### 🛠️ Technologies Used

| Technology | Description |
| --- | --- |
| **HTML5** | Content semantics, layout structuring, metadata handling, and form input controls. |
| **CSS3** | Visual skinning, linear typography scales, flexbox/grid alignments, and `@media print` directives. |
| **JavaScript (ES6+)** | Multi-array mapping, conditional validation gates, dynamic math formulas, and DOM updates. |

---

### ⚙️ Working Methodology

1. **Profile Registration**: The user enters identity parameters (Name, Register ID, School, Class, Exam Session) into the primary setup panel.
2. **Dynamic Subject Mounting**: Based on the chosen class and stream, JavaScript mounts the corresponding subject array into the table body.
3. **Marks Capture**: The operator keys in raw scores. Immediate visual checks guard against out-of-bounds metrics.
4. **Validation Logic Evaluation**: On clicking "Generate", the script checks compliance flags across all lines.
5. **Conditional Output Aggregation**: The app computes the cumulative average and checks pass statuses. For Class 12 students, it branches based on the pass flag to show either the cut-off breakdown or the reappear notice.
6. **Dynamic View Mount**: The presentation layer displays the complete, print-ready document immediately without a page refresh.

---

### 📌 Applications

* Portfolio development piece for front-end programming.
* Reference design for building dynamic data table structures.
* Educational template for learning complex DOM trees and array calculation wrappers in JavaScript.
* Practical/Record notebook submission for school or college lab tasks.

---

### 👨‍💻 Developer Information

* **Prepared by:** S. Rohith
* **Project Type:** Academic / Educational Mini-Project
* **Target Environment:** Client-Side Web Browsers (Standalone)
