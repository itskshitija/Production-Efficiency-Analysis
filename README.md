<a href="https://www.linkedin.com/in/kshitija-chilbule-b98515309/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin" alt="LinkedIn Badge" style="height: 30px; width: auto;">
</a>

# 📊 EcoDrive Innovations: Production Efficiency Analysis

Welcome to the **EcoDrive Innovations: Production Efficiency Analysis** project! This analysis evaluates the production performance of EcoDrive Innovations' centers by comparing actual outputs with targets. The project identifies trends, areas of concern, and opportunities for optimization.

# Access Google Sheets for the comprehensive overview of the project [Here](https://docs.google.com/spreadsheets/d/1_oNEUXCL014XnAtdXcZYxHZfKMfrUvAhPdCKmpfo_GY/edit?usp=sharing)

## 📝 Project Overview

### Objectives
1. **Production Center Performance:** Assess each production center's monthly and overall performance against targets.
2. **Company-Wide Analysis:** Evaluate company-level production trends for the first six months and identify areas for improvement.

### 🔠Dataset
**Target Production Data:** Monthly production targets for each center.
  
| **Production Center** | **Jan** | **Feb** | **Mar** | **Apr** | **May** | **Jun** |
|------------------------|---------|---------|---------|---------|---------|---------|
| Bangalore              | 4,600   | 3,800   | 3,700   | 3,800   | 4,100   | 4,000   |
| Chennai                | 4,700   | 4,400   | 4,400   | 4,700   | 4,800   | 4,700   |
| Mumbai                 | 3,600   | 3,700   | 4,000   | 4,100   | 4,100   | 4,200   |
| Delhi                  | 2,700   | 3,000   | 3,500   | 3,800   | 4,000   | 3,400   |
| Kolkata                | 3,800   | 4,500   | 4,700   | 4,100   | 4,200   | 4,000   |
| Ahmedabad              | 2,800   | 2,900   | 2,000   | 3,500   | 4,000   | 4,000   |
| Jaipur                 | 2,500   | 2,600   | 2,900   | 3,000   | 3,500   | 3,800   |

**Actual Production Data:** Monthly production outputs for each center.

| **Production Center** | **Jan** | **Feb** | **Mar** | **Apr** | **May** | **Jun** |
|------------------------|---------|---------|---------|---------|---------|---------|
| Bangalore              | 4,000   | 3,500   | 4,000   | 3,500   | 4,600   | 5,000   |
| Chennai                | 4,800   | 4,900   | 5,000   | 5,200   | 5,300   | 5,600   |
| Mumbai                 | 3,000   | 4,500   | 4,000   | 3,400   | 4,000   | 4,700   |
| Delhi                  | 2,300   | 3,000   | 4,200   | 3,900   | 4,200   | 3,900   |
| Kolkata                | 3,400   | 4,000   | 4,700   | 4,100   | 4,300   | 4,800   |
| Ahmedabad              | 2,200   | 2,500   | 2,500   | 3,500   | 4,000   | 4,800   |
| Jaipur                 | 2,000   | 2,300   | 2,500   | 2,600   | 2,700   | 3,000   |

## 📊Exploratory Data Analysis
### Production Overview
This section provides a summary of the total production and key performance metrics.

| **Metric**                     | **Value**       |
|---------------------------------|-----------------|
| **Total Production**            | 160,400         |
| **Number of Months**            | 6               |
| **Number of Production Centers**| 7               |
| **Average Production per Month**| 26,733.33       |
| **Average Production per Center**| 22,914.29      |

- **Total Production**:  
  Over 6 months, the total production across all centers reached **160,400 units**.

- **Average Monthly Production**:  
  On average, production across all centers was **26,733.33 units per month**, reflecting steady performance across the timeline.

- **Average Center Output**:  
  Each production center contributed an average of **22,914.29 units** over the 6 months.

### Month-wise Production Analysis
This section summarizes the production numbers for each month and highlights the months with the highest and lowest production.

| **Month** | **Production** |
|-----------|----------------|
| **Jan**   | 21,700         |
| **Feb**   | 24,700         |
| **Mar**   | 26,900         |
| **Apr**   | 26,200         |
| **May**   | 29,100         |
| **Jun**   | 31,800         |

- **Minimum Production**:  
  - **21,700 units** in January.  
  - Indicates a slower start to the year.

- **Maximum Production**:  
  - **31,800 units** in June.  
  - Reflects a significant increase in output over time.

- **Trend Analysis**:  
  - Production steadily increased month-on-month, with the highest jump observed between May and June.  
  - The data suggests improved performance as the year progressed.

### Production Center-wise Analysis

This section provides an overview of total production across different centers and highlights centers with the highest and lowest outputs.

| Production Center | Total Production | Target Achieved |  
|-------------------|------------------|-----------------|  
| **Bangalore**      | 24,600 units     | Yes             |  
| **Chennai**        | 30,800 units     | Yes (Top Performing) |  
| **Mumbai**         | 23,600 units     | No              |  
| **Delhi**          | 21,500 units     | Yes             |  
| **Kolkata**        | 25,300 units     | Yes             |  
| **Ahmedabad**      | 19,500 units     | Yes             |  
| **Jaipur**         | 15,100 units     | No (Underperforming) |  

- **Minimum Production**:  
  - **15,100 units** by **Jaipur**.  
  - Indicates room for improvement in production processes.

- **Maximum Production**:  
  - **30,800 units** by **Chennai**.  
  - Reflects the center's efficiency and high contribution to overall production.

- **Observations**:  
  - Chennai leads as the top-performing center, contributing **19.2%** of total production.  
  - Jaipur, while producing the least, still shows potential for growth with proper optimizations.

### Overall Performance Analysis
This section evaluates the month-wise performance by comparing target production to actual production and identifying whether targets were achieved or missed.
| **Month** | **Target Production** | **Actual Production** | **Target vs Actual** |
|-----------|------------------------|-----------------------|-----------------------|
| **Jan**   | 24,700                | 21,700               | **Target Missed**    |
| **Feb**   | 24,900                | 24,700               | **Target Missed**    |
| **Mar**   | 25,200                | 26,900               | **Target Achieved**  |
| **Apr**   | 27,000                | 26,200               | **Target Missed**    |
| **May**   | 28,700                | 29,100               | **Target Achieved**  |
| **Jun**   | 28,100                | 31,800               | **Target Achieved**  |

1. **Overall Target Achievement**:
   - Out of 6 months, targets were achieved in **3 months** (March, May, and June).
   - Performance improved consistently in Q2.

2. **Missed Targets**:
   - Targets were missed in **January, February, and April**, primarily due to lower-than-expected production.

3. **Best Month**:
   - **June** had the highest actual production of **31,800 units**, exceeding the target by **3,700 units**.

4. **Worst Month**:
   - **January** had the lowest actual production of **21,700 units**, missing the target by **3,000 units**.


### Overall Growth Trend
This section highlights the month-wise actual production and corresponding growth rates, showcasing the production trends over the reporting period.

| **Month** | **Actual Production** | **Growth Rate** |
|-----------|-----------------------|-----------------|
| **Jan**   | 21,700               | -               |
| **Feb**   | 24,700               | **13.82%**      |
| **Mar**   | 26,900               | **8.91%**       |
| **Apr**   | 26,200               | **-2.60%**      |
| **May**   | 29,100               | **11.07%**      |
| **Jun**   | 31,800               | **9.28%**       |

1. **Positive Growth**:
   - The production saw positive growth in **4 out of 5 months** after January, with the highest growth rate of **13.82%** in February.
   
2. **Negative Growth**:
   - A slight decline of **-2.60%** was observed in April compared to March, indicating potential production challenges.

3. **Steady Growth in Q2**:
   - May and June both experienced significant growth, with production peaking at **31,800 units** in June.

4. **Overall Growth Trend**:
   - The overall trend indicates consistent improvement in production, except for the minor dip in April.

### Growth Trends - Production Center
This section provides an overview of the actual monthly production and month-wise production growth rates for each production center.

| **Production Center** | **Jan**  | **Feb**  | **Mar**  | **Apr**  | **May**  | **Jun**  | **Feb Growth** | **Mar Growth** | **Apr Growth** | **May Growth** | **Jun Growth** |
|------------------------|----------|----------|----------|----------|----------|----------|----------------|----------------|----------------|----------------|----------------|
| **Bangalore**          | 4,000    | 3,500    | 4,000    | 3,500    | 4,600    | 5,000    | -13%           | 14%            | -13%           | 31%            | 9%             |
| **Chennai**            | 4,800    | 4,900    | 5,000    | 5,200    | 5,300    | 5,600    | 2%             | 2%             | 4%             | 2%             | 6%             |
| **Mumbai**             | 3,000    | 4,500    | 4,000    | 3,400    | 4,000    | 4,700    | 50%            | -11%           | -15%           | 18%            | 18%            |
| **Delhi**              | 2,300    | 3,000    | 4,200    | 3,900    | 4,200    | 3,900    | 30%            | 40%            | -7%            | 8%             | -7%            |
| **Kolkata**            | 3,400    | 4,000    | 4,700    | 4,100    | 4,300    | 4,800    | 18%            | 18%            | -13%           | 5%             | 12%            |
| **Ahmedabad**          | 2,200    | 2,500    | 2,500    | 3,500    | 4,000    | 4,800    | 14%            | 0%             | 40%            | 14%            | 20%            |
| **Jaipur**             | 2,000    | 2,300    | 2,500    | 2,600    | 2,700    | 3,000    | 15%            | 9%             | 4%             | 4%             | 11%            |

1. **Highest Growth**:
   - **Mumbai** experienced a significant 50% growth in February, highlighting a strong rebound from January's production.

2. **Consistent Growth**:
   - **Chennai** showcased steady growth, maintaining small but positive percentage increases every month.

3. **Fluctuating Performance**:
   - **Bangalore** and **Delhi** experienced growth fluctuations, with alternating months of positive and negative growth.

4. **Production Peaks**:
   - **Ahmedabad** and **Kolkata** demonstrated remarkable growth in April and June, with **Ahmedabad** peaking at **40% growth** in April.

5. **Stable Growth in Jaipur**:
   - Jaipur exhibited stable growth rates, with small but consistent increases throughout the period.

## 🚀Dashboard
![image](https://github.com/user-attachments/assets/198298c0-9b12-4fe7-9de7-5489824ad41b)


## 📈 Summary of Insights
1. June has been the most productive month, achieving the highest production output with 31,800 units
2.  January records the lowest production output, with only 21,700 units produced.
3.  The Chennai Production Center stands out as the top-performing facility, with a total production of 30,800 units.
4.  The Jaipur Production Center has underperformed, producing only 15,100 units, indicating an area of potential improvement.
