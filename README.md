# INFO 250 - Information Visualization (Project 2)
This is the README file for Team 2's Project 2 in the INFO 250 Information Visualization course, providing an overview of the project, team members, quick start guide, and core details.


## 1. Team Members
| Name         | Student ID       | Email                  | Role   |
|--------------|------------------|------------------------|--------|
| Qiao Ba      |                  |                        | Leader |
| Zhizhuo Yu   |                  |                        | Member |
| Yaojie Tian  | 320230942391     | tianyj2023@lzu.edu.cn  | Member |


## 2. Project Overview
### 2.1 Background & Goal
The project focuses on optimizing an existing population visualization chart. The original chart, based on World Bank data, compares the 1995 population and 2025 projected population of major Asian countries but suffers from critical design flaws (e.g., 3D bar distortion, inconsistent country ordering, poor color accessibility) that hinder accurate data comparison and pattern recognition.

Our goal is to redesign the visualization following information visualization principles, improving clarity, accessibility, and interactivity to help users better understand Asian population growth patterns and their implications for future food demand.

### 2.2 Core Improvements
- **Replace 3D with 2D Bars**: Eliminate perspective distortion for accurate height comparison.
- **Consistent Country Ordering**: Sort countries by population size to enable intuitive ranking.
- **Color Accessibility**: Adopt a color-blind-friendly palette, with color intensity linked to population growth magnitude.
- **Interactivity**: Add tooltips (for detailed population data) and an interactive Asian map (for spatial context).
- **Readable Labels**: Use horizontal bar charts and standardized country abbreviations to avoid tilted reading.

**original figure：**


<img width="769" height="476" alt="256e145bba841317d2e9339169e40cee" src="https://github.com/user-attachments/assets/ff821fa9-dae2-40b6-9ce0-1533dd6fef7f" />


**our figure：**


<img width="769" height="476" alt="image" src="https://github.com/user-attachments/assets/f10381e4-65ce-4f34-b2d0-695d4a7786b5" />


## 3. Quick Start
### 3.1 Prerequisites
Ensure Python 3.6+ and the following libraries are installed (install via `pip` if missing):
```bash
pip install pandas numpy matplotlib
```

### 3.2 Run the Visualization
1. Download the project files (including `visualization.py` and supporting data).
2. Open the terminal/command prompt and navigate to the project directory.
3. Execute the following command to generate and view the visualization:
   ```bash
   python visualization.py
   ```
4. After running, the optimized 2D bar chart and interactive Asian population map will automatically display. Hover over chart elements or map regions to view detailed data (e.g., 1995/2025 population, growth rate).


## 4. Key Visualization Insights
The redesigned visualization reveals critical patterns in Asian population change (1995–2025):
1. **Dominant Growth Drivers**: China (1.2B → 1.45B) and India (950M → 1.35B) account for most of Asia’s total population growth, with India narrowing the gap with China.
2. **Diverse Growth Trajectories**: Myanmar, Pakistan, and Bangladesh show fast growth; Indonesia, Vietnam, and Thailand have moderate growth; Japan’s growth is limited.
3. **Regional Aggregate Trend**: Asia’s total population grows from 2.7B to 3.8B (+1B+), highlighting significant demographic pressure.
4. **Uneven Growth**: Smaller countries (e.g., Philippines, Republic of Korea) have modest absolute growth but clear proportional changes (visible via tooltips).


## 5. Reference
- Data Source: World Bank Population Projections (1995, 2025)
- Community Sharing: https://mp.weixin.qq.com/s/QbLURtBjK2AU5QhI6P-T8g
