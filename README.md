# **Dynamic KPI Card Visual for Power BI**

This custom visual for Power BI creates dynamic, animated cards designed to display key performance indicators (KPIs) in an interactive and visually appealing format. It allows users to present multiple KPIs within a single visual, with each card representing different metrics such as current values, previous year comparisons, and budget values.

## **Features**

![image](https://github.com/user-attachments/assets/30f817ba-128d-48c5-a3ef-b62ca534e8be)


- **Dynamic Card Creation**: Automatically generates KPI cards based on the provided data, displaying key metrics including current values, previous year comparisons, and budget values.
- **Interactive Animations**: Cards feature smooth hover animations, revealing additional information like previous year and budget values when hovered over.
- **Customizable Styling**: The visual’s appearance can be easily customized via the centralized `StyleManager.ts`, allowing you to match your report's theme.
- **Responsive Design**: Cards adapt to various screen sizes and layout configurations, ensuring a consistent and clean presentation across different devices.

## **How to Use**

1. **Add the Visual to Your Report**:
   - Import the `.pbiviz` file generated from the build process into your Power BI report.

2. **Drag and Drop Fields**:
   - Drag and drop the fields into the appropriate data wells. Typically, you would assign:
     - `smeasureName` to the current value field.
     - `pyMeasureName` for the previous year's value.
     - `tmeasureName` for the budget value.

3. **Customize the Appearance**:
   - Customize the visual’s appearance using the formatting pane in Power BI. You can modify colors, fonts, and other visual properties to align with your report’s theme.

4. **Interactivity**:
   - Hover over the cards to view animations and reveal additional information like previous year and budget comparisons.


## **Contributing**

Feel free to contact me to contribute to the project!

## **License**

1. **Ownership**:
   - The Dynamic KPI Card Visual for Power BI is the exclusive property of MabCap Inc. All intellectual property rights, including copyrights, trademarks, and patents, are retained by MabCap Inc.

2. **License Grant**:
   - MabCap Inc. grants you a non-exclusive, non-transferable license to use this software for personal or internal business purposes only.
   - Redistribution, sublicensing, or any other form of distribution to third parties is strictly prohibited without prior written consent from MabCap Inc.

3. **Restrictions**:
   - You are prohibited from selling, leasing, or renting this software, either in its original form or any modified version.
   - You may not reverse engineer, decompile, or disassemble the software, except as expressly permitted by applicable law.

4. **Modification**:
   - You may modify the software for personal or internal use. However, any modified version remains subject to the terms of this license and cannot be distributed, sold, or otherwise shared with third parties.


5. **Termination**:
   - This license is effective until terminated. Upon termination, you must cease all use of the software and destroy all copies of it, including any modifications.

6. **Disclaimer of Warranty**:
   - The software is provided "as is," without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement. MabCap Inc. does not warrant that the software will meet your requirements or that its operation will be uninterrupted or error-free.

7. **Limitation of Liability**:
   - In no event shall MabCap Inc. be liable for any special, incidental, indirect, or consequential damages whatsoever arising out of the use of or inability to use the software.

## **Contact Information**

For inquiries or further information, please contact:

**MabCap Inc.**  
© 2024 MabCap Inc. All rights reserved.

