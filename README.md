# Titanic Survival Analysis

My first data analysis project where I explored the Titanic dataset to understand what factors influenced passenger survival.

## Project Overview

This project analyzes the famous Titanic dataset to answer questions like:
- What was the overall survival rate?
- Did gender affect survival chances?
- Did passenger class matter?
- Did age play a role?
- Did traveling with family help or hurt?
- Did ticket fare (price) affect survival?

## Key Findings

After analyzing 891 passengers, I discovered:

1. **Gender was the biggest factor:** Women had 74% survival rate vs men at 19%
2. **Class mattered a lot:** 1st class had 63% survival, 3rd class only 24%
3. **Children were protected:** Kids under 12 had 58% survival rate
4. **Small families survived better:** Families of 2-4 had best chances
5. **Money helped:** Higher ticket prices = better survival

### The harsh reality:
- Poor, male, 3rd-class passenger = ~15% survival chance
- Wealthy, female, 1st-class passenger = ~90% survival chance

## Tools & Technologies

- **Python 3**
- **Pandas** - data manipulation
- **Matplotlib & Seaborn** - visualizations
- **Jupyter Notebook** - analysis environment

## Project Structure
```
titanic-analysis/
│
├── titanic_analysis.ipynb    # Main analysis notebook
├── data/
│   └── Titanic-Dataset.csv   # Dataset
├── images/                    # Saved visualizations
│   ├── survival_count.png
│   ├── gender_survival.png
│   ├── class_survival.png
│   ├── age_survival.png
│   ├── family_survival.png
│   ├── fare_survival.png
│   └── port_survival.png
└── README.md                  # This file
```

## How to Run

1. Clone this repository:
```bash
git clone https://github.com/shubhamjais04/titanic-analysis.git
cd titanic-analysis
```

2. Install required libraries:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Open Jupyter Notebook:
```bash
jupyter notebook titanic_analysis.ipynb
```

4. Run all cells to see the analysis!

## Visualizations

The project includes several visualizations:
- Survival rate comparisons
- Gender-based analysis
- Class-based analysis
- Age distribution analysis
- Family size impact
- Fare correlation

Check the `images/` folder for all saved plots.

## 💭 What I Learned

**Technical Skills:**
- Handling missing data (used median for Age, mode for Embarked)
- Data cleaning and preprocessing
- Creating meaningful visualizations
- Feature engineering (FamilySize, AgeGroup, FareGroup)
- Pandas groupby and aggregations

**Challenges:**
- Dealing with 77% missing Cabin data (decided to drop it)
- Choosing appropriate visualizations
- Creating meaningful age groups
- Making insights clear and actionable

**Next Steps:**
- Build a machine learning model to predict survival
- Analyze passenger titles (Mr., Mrs., etc.)
- Try advanced visualization techniques

## Dataset

**Source:** Kaggle - Titanic Dataset

**Description:** Contains information about 891 passengers including:
- Demographics (age, gender)
- Socioeconomic status (class, fare)
- Family relations (siblings, parents, children)
- Embarkation details
- Survival status

## 🙏 Acknowledgments

- Dataset from Kaggle's Titanic competition
- Inspired by various data science tutorials
- First project in my data science journey!

## 📧 Contact

**Shubham Jaiswal**
- Email: shubhjais.in@gmail.com
- LinkedIn: [linkedin.com/in/shubhamjaiswal2004](https://linkedin.com/in/shubhamjaiswal2004)
- GitHub: [@shubhamjais04](https://github.com/shubhamjais04)

---

⭐ If you found this project helpful, please give it a star!

---

**Status:** Completed ✅  
**Last Updated:** February 2026