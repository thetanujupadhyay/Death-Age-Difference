# Analysis of Lifespan Differences Between Left-Handed and Right-Handed Individuals

### A Bayesian Statistical Investigation into the "Left-Handed Early Death" Myth

---

## 📖 Project Overview

This project provides a comprehensive statistical investigation into the long-standing claim that left-handed individuals have a shorter average lifespan[cite: 26]. The analysis employs Bayesian inference to test whether this observed difference is a genuine biological phenomenon or a statistical artifact resulting from historical shifts in the societal acceptance and reporting of left-handedness[cite: 27, 44].

By constructing and comparing probability distributions for age at death conditional on handedness—P(Age | Handedness)—for two different time periods (a historical 1990 scenario and a contemporary 2018 scenario), this study demonstrates that the lifespan gap is primarily a result of demographic trends[cite: 31, 48].

---

## 📊 Interactive Infographic

For a high-level visual summary of the project's data, methodology, and findings, please view the live, interactive infographic.

**[➡️ View the Live Infographic Here](https://thetanujupadhyay.github.io/Death-Age-Difference/)**

#### Preview
[![Infographic Preview](https://github.com/user-attachments/assets/0df02595-ac0c-4b87-a07f-f6a84bfebe97)
  )](https://thetanujupadhyay.github.io/Death-Age-Difference/)

---

## 🎯 Key Findings

| Metric | 1990 Scenario | 2018 Scenario | Change |
| :--- | :--- | :--- | :--- |
| **Mean Age (Left-handed)** | 67.3 years  | 70.3 years  | +3.0 years |
| **Mean Age (Right-handed)** | 72.4 years  | 72.4 years  | 0.0 years |
| **Mortality Gap** | **5.1 years**  | **2.1 years**  | **-3.0 years** |
| **Gap Reduction** | - | - | **59%**  |

**Conclusion:** The findings provide compelling evidence that the observed lifespan difference is a **statistical artifact**. The historical increase in the reporting of left-handedness created a demographic bias, rather than reflecting a biological predisposition to premature mortality.

---

## 📚 Data Sources

This analysis utilizes two primary datasets:

1.  **Left-Handedness Rates:** Sourced from a 1986 National Geographic survey, as analyzed by Gilbert and Wysocki (1992). This data shows the changing rates of left-handedness by age and sex.
2.  **Death Distribution Data:** Sourced from the U.S. Centers for Disease Control and Prevention (CDC) for the year 1999. This provides the overall age distribution of deaths in the population.

---

## 🧠 Methodology

The core of this analysis is **Bayes' theorem**, which is used to calculate the conditional probability of dying at a certain age given an individual's handedness.

The formula applied is:
$$ P(A | LH) = \frac{P(LH | A) \cdot P(A)}{P(LH)} $$

Where:
* **$P(A | LH)$**: The probability of dying at age A, given left-handedness.
* **$P(LH | A)$**: The probability of being left-handed, given death at age A (derived from survey data based on birth year).
* **$P(A)$**: The overall probability of dying at age A (derived from national death distribution data).
* **$P(LH)$**: The overall probability of being left-handed in the deceased population.

The analysis calculates and compares the mean of the resulting probability distributions for both left-handed and right-handed populations for the years 1990 and 2018.

---

## 📈 Exploratory Data Analysis

### 1. Left-Handedness Rates by Age and Sex (1986 Survey)
The initial data shows a clear trend where the percentage of reported left-handers decreases with age. This reflects a cultural shift rather than a survival effect, as older generations were more likely to be forced to write with their right hand.


### 2. Left-Handedness Rates by Birth Year
When converted to show rates by birth year, the data clearly illustrates the increasing social acceptance of left-handedness throughout the 20th century. This is the key demographic trend that creates the statistical artifact.


### 3. U.S. Death Distribution (1999)
The CDC data provides the baseline probability of death at each given age, $P(A)$. It shows a typical mortality curve with a peak in the elderly years, which is characteristic of a developed nation.


---

## 🔬 Results & Comparative Analysis

### Scenario 1: Historical Analysis (1990 Study Year)

This scenario models the demographic conditions of 1990, the period when claims about the mortality disadvantage for left-handers were established. The probability distributions show a clear separation, with the left-handed population having a higher probability of death at younger ages, leading to a significant difference in average lifespan.


| Handedness | Mean Age at Death (1990) |
| :--- | :--- |
| Left-Handed | 67.3 years |
| Right-Handed | 72.4 years |
| **Difference** | **5.1 years**|

### Scenario 2: Contemporary Re-evaluation (2018 Study Year)

This analysis is repeated for 2018 demographic conditions, where left-handedness rates have largely stabilized across generations. As the cultural bias has faded, the age-at-death distributions for both groups converge, and the apparent mortality gap nearly vanishes.


| Handedness | Mean Age at Death (2018) |
| :--- | :--- |
| Left-Handed | 70.3 years |
| Right-Handed | 72.4 years |
| **Difference** | **2.1 years** |

---

## 🎯 Conclusion

The analysis conclusively demonstrates that the "shorter lifespan" of left-handed individuals is a **statistical artifact**, not a biological reality. The gap in average age at death, prominent in older data, is a direct result of changing cultural norms. As society became more accepting of left-handedness, the number of people identifying as left-handed increased in younger generations, creating a temporary statistical illusion that has since vanished.

---

## 🚀 Future Scope

1.  **International Validation:** Apply this methodology to data from other countries to test the hypothesis across different cultural contexts.
2.  **Cause-Specific Analysis:** Investigate potential handedness-related differences for specific causes of death, such as accidents or neurological conditions.
3.  **Broader Applications:** Use this Bayesian framework to investigate other apparent health disparities that may be influenced by changing social attitudes over time (e.g., mental health, sexual orientation).

---

## ⚙️ How to Run

* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib
* **Environment:** The analysis was conducted in the provided Jupyter Notebook (`Analyze_Death_Age_Difference_of_Right_Handers_with_Left_Handers_Project.ipynb`).

To run the analysis yourself, you can open and execute the cells within the Jupyter Notebook file.
