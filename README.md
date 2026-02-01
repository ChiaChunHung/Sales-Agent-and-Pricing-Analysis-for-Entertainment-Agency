z# TuneWorks Entertainment Agency Analytics

> Data-Driven Insights for Entertainment Agency Growth

[![SQL](https://img.shields.io/badge/SQL-PostgreSQL-blue.svg)](https://www.postgresql.org/)
[![Python](https://img.shields.io/badge/Python-3.x-yellow.svg)](https://www.python.org/)
[![AI-Assisted](https://img.shields.io/badge/AI-ChatGPT%20%7C%20Gemini-green.svg)](https://openai.com/)

## 📋 Project Overview

TuneWorks is a mid-sized entertainment agency managing entertainers, clients, and bookings. Despite having a robust data engineering infrastructure, they lack an in-house analytics function. This project, conducted by **McBrainsey & Co.**, delivers comprehensive SQL-based analysis and AI-assisted exploration to unlock the value of their operational data.

### Business Challenge

- **Untapped Data Value**: Large volumes of operational data exist but aren't leveraged for strategic decision-making
- **No Analytics Function**: Lack of in-house capability for sophisticated data analysis
- **Limited Insights**: Unable to identify patterns across entertainers, agents, customers, and engagements
- **Reactive Management**: Decisions based on intuition rather than data-driven evidence

### Project Mission

Transform TuneWorks' raw data into actionable business intelligence through:
- Comprehensive data exploration and quality assessment
- Discovery of patterns and relationships across key business entities
- Quantification of key performance indicators
- Development of strategic recommendations for talent management, pricing optimization, and client segmentation
- Comparison of independent SQL analysis with AI-assisted insights

---

## 🎯 Objectives

1. **Data Familiarization**: Thoroughly understand dataset structure, relationships, and business meaning
2. **Data Quality Assessment**: Identify and address data quality issues (missing values, duplicates, inconsistencies)
3. **Exploratory Analysis**: Discover patterns and trends across business entities
4. **Business Metrics**: Quantify KPIs (revenue, booking frequency, engagement duration, entertainer popularity)
5. **Strategic Recommendations**: Develop actionable strategies for business growth
6. **AI Collaboration**: Compare manual SQL analysis with AI-assisted insights

---

## 📊 Dataset Overview

The TuneWorks dataset consists of **12 interconnected tables**:

### Core Business Tables
- **Agents**: Agency representatives (11 fields including salary, commission rate)
- **Customers**: Client information and contact details (8 fields)
- **Engagements**: Booking contracts linking customers, agents, and entertainers (9 fields)
- **Entertainers**: Performer information and contact details (10 fields)

### Supporting Tables
- **Entertainer_Members**: Maps entertainers to individual members (bands/groups)
- **Entertainer_Styles**: Musical style proficiency for each entertainer
- **Members**: Individual performer details
- **Musical_Preferences**: Customer music style preferences
- **Musical_Styles**: Master list of music genres
- **Time Dimension Tables**: ztblDays, ztblMonths (for temporal analysis)

---

## 🔬 Methodology

### Phase 1: Data Familiarization & Documentation
**Team**: Mitchell Ma, Joshua Zhang

- Understand every table and field in the dataset
- Create comprehensive data dictionary
- Map relationships between tables
- Identify unclear or ambiguous fields

### Phase 2: Data Preparation & Cleaning
**Team**: Alizeh Sultan, Yutong Gao, Shao-Chueh Liu

- Evaluate data quality
- Correct data inconsistencies
- Handle missing values and outliers
- Assess data completeness

### Phase 3: Exploratory Analysis & Insight Generation
**Team**: Tony Hung, Xiaoyu Ma, Maria Chen

- Univariate analysis (summary statistics, visualizations)
- Multivariate analysis (correlations, regressions)
- Cross-table analysis (agent performance, entertainer popularity)
- Pattern identification and metric quantification

### Phase 4: Synthesis & Recommendations
**Team**: All Members

- Synthesize findings into actionable business strategies
- Develop proposals for talent management, pricing, and client segmentation
- Compare independent analysis with AI-assisted insights
- Prepare executive presentation and technical reports

---

## 🛠️ Tools & Technologies

### SQL Analysis
- **PostgreSQL** - Database for querying and analysis
- **Advanced SQL techniques** - Joins, aggregations, window functions, CTEs

### AI Collaboration
- **ChatGPT/Gemini** - EDA guidance and query generation
- **Python** - Data visualization (pandas, matplotlib, seaborn)
- **Google Colab** - Running Python code

### Presentation & Documentation
- **Microsoft PowerPoint** - Executive presentation
- **Microsoft Word/Google Docs** - Technical reports

---

## 📦 Key Deliverables

### 1. Technical Report (Internal Use)
- Complete data dictionary for all 12 tables
- All SQL queries and analysis steps
- Data quality assessment and remediation notes
- Analytical thought process and observations
- Data visualizations (charts, tables, plots)

### 2. ChatGPT/AI Collaboration Report
- Prompts and responses from ChatGPT/Gemini
- AI-generated SQL queries and results
- Python code for data visualization
- AI-generated presentation materials

### 3. Executive Presentation (Client-Facing)
- Key findings and actionable recommendations
- KPIs and visual summaries
- Data-backed strategic narrative
- Professional, visually engaging slides
- 6-8 minute presentation

### 4. Key Takeaways: Learning to Work with AI
- Comparison of AI vs. manual analysis strengths
- Lessons learned from combined approaches
- Best practices for human-AI collaboration in analytics

---

## 💡 Expected Outcomes

### Business Value for TuneWorks
✅ **Data-Driven Decision Making**: Move from intuition-based to evidence-based strategic planning  
✅ **Operational Efficiency**: Identify and optimize underperforming areas  
✅ **Revenue Growth**: Discover untapped market opportunities and optimize pricing strategies  
✅ **Customer Satisfaction**: Better match entertainers to customer preferences  
✅ **Competitive Advantage**: Leverage analytics capabilities competitors may lack  

### Learning Outcomes for Team
✅ Practical SQL proficiency in complex database analysis  
✅ EDA methodology and best practices  
✅ Data storytelling and executive presentation skills  
✅ AI tool proficiency for data analysis  
✅ Understanding strengths and limitations of AI vs. human analysis  

---

## 📈 Success Criteria

| Category | Weight | Focus Areas |
|----------|--------|-------------|
| **Technical Excellence** | 25% | SQL analysis completeness, data dictionary quality, data quality assessment |
| **Executive Presentation** | 30% | Quality of insights, slide design, storytelling, time management |
| **AI Collaboration** | 25% | Effective AI tool use, Python visualizations, AI vs. manual comparison |
| **Learning Reflection** | 10% | Understanding AI strengths/limitations, human-AI synergies |
| **Individual Performance** | 10% | Presentation delivery, team contribution, professionalism |

---

## 👥 Team

**McBrainsey & Co. Consulting Team**

### Phase 1 Team
- Mitchell Ma
- Joshua Zhang

### Phase 2 Team
- Alizeh Sultan
- Yutong Gao
- Shao-Chueh Liu

### Phase 3 Team
- Tony Hung
- Xiaoyu Ma
- Maria Chen

---

## 📚 Project Resources

- TuneWorks Entertainment Dataset (12 tables, PostgreSQL)
- EDA Concept Guide
- Final Project Case Instructions
- SQL Project Planning Document
- Technical Report Template

---

## 🚀 Getting Started

### Prerequisites
```bash
# Install PostgreSQL
# Install Python 3.x
# Install required Python packages
pip install pandas matplotlib seaborn jupyter
```

### Database Setup
```sql
-- Connect to PostgreSQL
psql -U username -d tuneworks_db

-- Verify tables
\dt
```

### Running Analysis
```python
# Example Python analysis
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Connect to database and run queries
# Generate visualizations
# Export results
```

---

## 📝 License

This project is part of an academic consulting engagement with TuneWorks Entertainment Agency.

---

## 🤝 Contributing

This is a team project. For questions or suggestions, please contact the project team members.

---

## 📧 Contact

**McBrainsey & Co.**  
Consulting Team - TuneWorks Analytics Project

---

## 🙏 Acknowledgments

- TuneWorks Entertainment Agency for providing the dataset
- Instructors for guidance and EDA concept materials
- ChatGPT/Gemini for AI-assisted analysis support

---

**Last Updated**: January 2026  
**Project Status**: In Progress  
**Client**: TuneWorks Entertainment Agency
