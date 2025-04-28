# 📄 Glitch Quality Analysis Project

## 📋 Overview
This project involves performing descriptive analysis, creating glitch reports with specific color coding, and building a quality analysis dashboard using Google Sheet features like PivotTables, Sparklines, Slicers, VLOOKUP, IF functions, and Charts.

---

### Task 1: Setup and Descriptive Analysis

* ➕ Add a new tab and rename it to "Working Note".
* ➕ Add another tab and rename it to "Descriptive Analysis".
* 📊 Perform a descriptive analysis of the given data.
* 📸 Ensure the output matches the provided screenshot.

 
![image](https://github.com/user-attachments/assets/afc703ea-b336-44ad-a666-ebea46cf2d31)


---


### Task 2: Glitch QA Report and Color Coding

* ➕ Add a new tab and rename it to "Glitch QA Report".

#### Color Coding Rules 🎨

* Total Major Glitches bar: #334960
* Total Minor Glitches bar: #f46524
* Major glitches in a part > average: Red #D81010 🟥 or Green #0C9409 🟩
* Minor glitches in a part > average: Red #D81010 🟥 or Green #0C9409 🟩

#### Hint 💡

* Use the following formula for conditional sparkline formatting:

    ```excel
    IF(B7<AVERAGE($B$7:$B$13), SPARKLINE(B7, {"charttype","bar";"max",max($B$7:$B$13);"color1","#0C9409"}), SPARKLINE(B7, {"charttype","bar";"max",min($B$7:$B$13);"color1","#D81010"})
    ```

* Ensure your answer matches the provided screenshot.


Your answer should match the below screenshot:
![image](https://github.com/user-attachments/assets/f1d634ee-a5cd-418b-8b5f-40bb0d77e07b)

---
### Task 3: Build the Quality Analysis Dashboard

* ➕ Add a new tab and rename it to "Quality Analysis Dashboard".
* 🛠️ Build the dashboard as shown in the provided screenshot.

#### Dashboard Features 🧩

* Slicer 1: Glitch Type → Select Major.
* Slicer 2: Part Category → Select the top 2 part categories.
* 📸 Ensure the dashboard matches exactly with the reference image.
  
![image](https://github.com/user-attachments/assets/20e0f6c1-18d4-41dd-b8fd-c7c927be09c9)
---

#### Tools and Features Used ⚙️

* PivotTables
* Sparklines
* Slicers
* Charts
* VLOOKUP
* IF Functions






Hint:

 Slicers 1 :Glitch Type : Major

 Slicers 2: Part_Category: Select top 2 part categories.
