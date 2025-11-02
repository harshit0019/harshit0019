# Hi, I'm Harshit Yadav 👋

**Data Analyst | Power BI Developer | Python Enthusiast**

I transform complex data into actionable insights through interactive dashboards, advanced analytics, and automation. With expertise in Power BI, Python, and SQL, I help organizations make data-driven decisions that drive real business impact.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](your-linkedin-url)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:your.email@domain.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-4285F4?style=flat&logo=google-chrome&logoColor=white)](your-portfolio-url)

---

## 🎯 What I Do

- **Business Intelligence**: Design and develop Power BI dashboards that turn data into strategic insights
- **Data Analysis**: Extract meaningful patterns from complex datasets using Python and SQL
- **Analytics Automation**: Build ETL pipelines and automated reporting solutions
- **Data Storytelling**: Create compelling visualizations that communicate insights clearly to stakeholders

---

## 🛠️ Technical Skills

**Analytics & Visualization**
```
Power BI • DAX • Power Query (M) • Tableau • Excel (Advanced)
```

**Programming & Data Science**
```
Python • SQL • Pandas • NumPy • Scikit-learn • Matplotlib • Plotly
```

**Databases & Tools**
```
PostgreSQL • MySQL • SQL Server • Git • Jupyter • VS Code
```

**Additional Expertise**
```
Data Modeling • ETL/ELT • Statistical Analysis • A/B Testing • KPI Development
API Integration • Web Scraping • Prompt Engineering • Documentation
```

## 📈 GitHub Analytics

![Harshit's GitHub Stats](https://github-readme-stats.vercel.app/api?username=harshit0019&show_icons=true&theme=default&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=harshit0019&layout=compact&theme=default&hide_border=true)

---

## 📚 Recent Work & Learning

🔭 **Currently Working On**
- Building a custom Power BI custom visual library
- Developing an AI-assisted data analysis tool using LangChain
- Contributing to open-source analytics projects

🌱 **Currently Learning**
- Advanced DAX patterns and optimization techniques
- Azure Data Factory and cloud-based analytics
- Real-time streaming analytics with Python

📝 **Writing About**
- Power BI best practices and DAX tricks
- Python automation for data analysts
- Data visualization principles

---

## 🎓 Certifications & Education

- **Microsoft Certified: Data Analyst Associate** (Power BI)
- **Microsoft Certified: Azure Data Fundamentals**
- **Python for Data Science** - Coursera/DataCamp
- **Advanced SQL for Data Analysis** - [Platform]
- **Bachelor's in [Your Field]** - [University Name]

---

## 💻 Code Example

Here's a sample of my work - a Python function for automated data quality checks:
```python
import pandas as pd
from typing import Dict, List

def data_quality_report(df: pd.DataFrame) -> Dict[str, any]:
    """
    Generate comprehensive data quality metrics
    """
    report = {
        'total_rows': len(df),
        'total_columns': len(df.columns),
        'missing_values': df.isnull().sum().to_dict(),
        'missing_percentage': (df.isnull().sum() / len(df) * 100).to_dict(),
        'duplicates': df.duplicated().sum(),
        'data_types': df.dtypes.to_dict(),
        'memory_usage': f"{df.memory_usage(deep=True).sum() / 1024**2:.2f} MB"
    }
    
    # Identify columns with high missing rates
    high_missing = {k: v for k, v in report['missing_percentage'].items() if v > 10}
    report['high_missing_columns'] = high_missing
    
    return report

# Usage
quality_metrics = data_quality_report(your_dataframe)
```

---

## 🤝 Let's Collaborate

I'm always interested in:
- **Data analytics projects** that create business value
- **Open-source contributions** in the analytics space
- **Consulting opportunities** for Power BI implementations
- **Knowledge sharing** through blogging and community engagement

---

## 📫 Get In Touch

- 💼 **LinkedIn**: [linkedin.com/in/yourprofile](your-linkedin)
- 📧 **Email**: your.email@domain.com
- 🌐 **Portfolio**: [yourportfolio.com](your-portfolio)
- 📝 **Blog**: [yourblog.com](your-blog)
- 🐦 **Twitter**: [@yourhandle](your-twitter)

---

## 📊 Quick Stats
```javascript
const harshit = {
    code: ["Python", "SQL", "DAX", "M", "JavaScript"],
    tools: {
        bi: ["Power BI", "Tableau", "Excel"],
        dataScience: ["Pandas", "NumPy", "Scikit-learn", "Matplotlib"],
        databases: ["SQL Server", "PostgreSQL", "MySQL"],
        cloud: ["Azure", "Power Platform"],
        other: ["Git", "Jupyter", "Streamlit", "VS Code"]
    },
    focus: "Turning data into decisions",
    location: "India",
    availability: "Open to opportunities"
};
```

---

<div align="center">

**💡 "Data is the new oil, but analytics is the refinery."**

![Profile Views](https://komarev.com/ghpvc/?username=harshit0019&color=0e75b6&style=flat)

⭐️ From [harshit0019](https://github.com/harshit0019)

</div>
