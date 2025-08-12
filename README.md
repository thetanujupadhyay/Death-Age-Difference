# Analysis of Lifespan Differences Between Left-Handed and Right-Handed Individuals

### A Bayesian Statistical Investigation into the "Left-Handed Early Death" Myth

---

## 📖 Project Overview

[cite_start]This project provides a comprehensive statistical investigation into the long-standing claim that left-handed individuals have a shorter average lifespan[cite: 26]. [cite_start]The analysis employs Bayesian inference to test whether this observed difference is a genuine biological phenomenon or a statistical artifact resulting from historical shifts in the societal acceptance and reporting of left-handedness[cite: 27, 44].

[cite_start]By constructing and comparing probability distributions for age at death conditional on handedness—P(Age | Handedness)—for two different time periods (a historical 1990 scenario and a contemporary 2018 scenario), this study demonstrates that the lifespan gap is primarily a result of demographic trends[cite: 31, 48].

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
| **Mean Age (Left-handed)** | [cite_start]67.3 years [cite: 32] | [cite_start]70.3 years [cite: 33] | +3.0 years |
| **Mean Age (Right-handed)** | [cite_start]72.4 years [cite: 32] | [cite_start]72.4 years [cite: 33] | 0.0 years |
| **Mortality Gap** | [cite_start]**5.1 years** [cite: 32] | [cite_start]**2.1 years** [cite: 33] | **-3.0 years** |
| **Gap Reduction** | - | - | [cite_start]**59%** [cite: 898] |

[cite_start]**Conclusion:** The findings provide compelling evidence that the observed lifespan difference is a **statistical artifact**[cite: 34]. [cite_start]The historical increase in the reporting of left-handedness created a demographic bias, rather than reflecting a biological predisposition to premature mortality[cite: 35].

---

## 📚 Data Sources

This analysis utilizes two primary datasets:

1.  [cite_start]**Left-Handedness Rates:** Sourced from a 1986 National Geographic survey, as analyzed by Gilbert and Wysocki (1992)[cite: 29, 50]. This data shows the changing rates of left-handedness by age and sex.
2.  [cite_start]**Death Distribution Data:** Sourced from the U.S. Centers for Disease Control and Prevention (CDC) for the year 1999[cite: 29, 52]. This provides the overall age distribution of deaths in the population.

---

## 🧠 Methodology

[cite_start]The core of this analysis is **Bayes' theorem**, which is used to calculate the conditional probability of dying at a certain age given an individual's handedness[cite: 28, 214].

The formula applied is:
$$ P(A | LH) = \frac{P(LH | A) \cdot P(A)}{P(LH)} $$

Where:
* [cite_start]**$P(A | LH)$**: The probability of dying at age A, given left-handedness[cite: 222].
* [cite_start]**$P(LH | A)$**: The probability of being left-handed, given death at age A (derived from survey data based on birth year)[cite: 223].
* [cite_start]**$P(A)$**: The overall probability of dying at age A (derived from national death distribution data)[cite: 224].
* [cite_start]**$P(LH)$**: The overall probability of being left-handed in the deceased population[cite: 225].

[cite_start]The analysis calculates and compares the mean of the resulting probability distributions for both left-handed and right-handed populations for the years 1990 and 2018[cite: 48].

---

## 📈 Exploratory Data Analysis

### 1. Left-Handedness Rates by Age and Sex (1986 Survey)
[cite_start]The initial data shows a clear trend where the percentage of reported left-handers decreases with age[cite: 147]. [cite_start]This reflects a cultural shift rather than a survival effect, as older generations were more likely to be forced to write with their right hand[cite: 624].


### 2. Left-Handedness Rates by Birth Year
[cite_start]When converted to show rates by birth year, the data clearly illustrates the increasing social acceptance of left-handedness throughout the 20th century[cite: 648, 670]. This is the key demographic trend that creates the statistical artifact.


### 3. U.S. Death Distribution (1999)
The CDC data provides the baseline probability of death at each given age, $P(A)$. [cite_start]It shows a typical mortality curve with a peak in the elderly years, which is characteristic of a developed nation[cite: 672, 730].


---

## 🔬 Results & Comparative Analysis

### Scenario 1: Historical Analysis (1990 Study Year)

[cite_start]This scenario models the demographic conditions of 1990, the period when claims about the mortality disadvantage for left-handers were established[cite: 753]. [cite_start]The probability distributions show a clear separation, with the left-handed population having a higher probability of death at younger ages, leading to a significant difference in average lifespan[cite: 791].


| Handedness | Mean Age at Death (1990) |
| :--- | :--- |
| Left-Handed | [cite_start]67.3 years [cite: 807] |
| Right-Handed | [cite_start]72.4 years [cite: 808] |
| **Difference** | [cite_start]**5.1 years** [cite: 810]|

### Scenario 2: Contemporary Re-evaluation (2018 Study Year)

[cite_start]This analysis is repeated for 2018 demographic conditions, where left-handedness rates have largely stabilized across generations[cite: 833]. [cite_start]As the cultural bias has faded, the age-at-death distributions for both groups converge, and the apparent mortality gap nearly vanishes[cite: 887, 834].


| Handedness | Mean Age at Death (2018) |
| :--- | :--- |
| Left-Handed | [cite_start]70.3 years [cite: 894] |
| Right-Handed | [cite_start]72.4 years [cite: 894] |
| **Difference** | [cite_start]**2.1 years** [cite: 895] |

---

## 🎯 Conclusion

[cite_start]The analysis conclusively demonstrates that the "shorter lifespan" of left-handed individuals is a **statistical artifact**, not a biological reality[cite: 985]. [cite_start]The gap in average age at death, prominent in older data, is a direct result of changing cultural norms[cite: 943]. [cite_start]As society became more accepting of left-handedness, the number of people identifying as left-handed increased in younger generations, creating a temporary statistical illusion that has since vanished[cite: 989].

---

## 🚀 Future Scope

1.  [cite_start]**International Validation:** Apply the same methodology to data from other countries to test the hypothesis across different cultural contexts[cite: 1017].
2.  [cite_start]**Cause-Specific Analysis:** Investigate potential handedness-related differences for specific causes of death, such as accidents or neurological conditions[cite: 1021].
3.  [cite_start]**Broader Applications:** Use this Bayesian framework to investigate other apparent health disparities that may be influenced by changing social attitudes over time (e.g., mental health, sexual orientation)[cite: 965, 1044].

---

## ⚙️ How to Run

* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib
* **Environment:** The analysis was conducted in the provided Jupyter Notebook (`Analyze_Death_Age_Difference_of_Right_Handers_with_Left_Handers_Project.ipynb`).

To run the analysis yourself, you can open and execute the cells within the Jupyter Notebook file.
