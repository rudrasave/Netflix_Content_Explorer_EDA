# 🎬 Netflix Content Explorer
## Comprehensive Exploratory Data Analysis with Real Data

---

## 📊 **Project Overview**

This is a complete, professional-grade data analysis project exploring **real Netflix content data** with:
- **5,850 titles** (movies and TV shows)
- **77,801 cast & crew records**
- **109 countries** represented
- **51,308 unique actors**
- **3,444 unique directors**

---

## ✅ **What's Included - ALL Deliverables**

### 1. **📓 Jupyter Notebook** (Google Colab Ready)
- File: `Netflix_Content_Explorer_Complete.ipynb`
- All analysis cells ready to run
- Step-by-step code with explanations
- **Copy-paste friendly** for Google Colab

### 2. **🐍 Python Analysis Script**
- File: `netflix_complete_analysis.py`
- Complete standalone Python script
- Generates all 8 visualizations
- Run with: `python netflix_complete_analysis.py`

### 3. **📊 8 Professional Visualizations** (PNG files)
1. `01_content_type_analysis.png` - Movies vs Shows breakdown
2. `02_genre_distribution.png` - Top 15 genres
3. `03_content_trends_over_time.png` - Release year analysis
4. `04_country_production.png` - Geographic distribution
5. `05_top_directors_actors.png` - Top talent analysis
6. `06_rating_patterns.png` - IMDB score distribution
7. `07_runtime_duration_analysis.png` - Duration statistics
8. `08_age_certification_analysis.png` - Content ratings

### 4. **📄 Your Original Data Files**
- `titles.csv` - 5,850 Netflix titles
- `credits.csv` - 77,801 cast/crew records

### 5. **📖 This README** - Complete documentation

---

## 🎯 **Analysis Coverage (ALL 6 Points)**

✅ **1. Content Trends Over Time**
   - Yearly release patterns (1945-2022)
   - Decade-wise distribution
   - Movies vs Shows evolution

✅ **2. Genre Distribution**
   - 19 unique genres analyzed
   - Top 15 genres identified
   - Drama leads with 2,968 titles (50.7%)

✅ **3. Country-Wise Content Production**
   - 109 countries represented
   - US leads with 2,323 titles (39.7%)
   - Strong Indian, British, Japanese presence

✅ **4. Top Directors/Actors**
   - 51,308 unique actors
   - 3,444 unique directors
   - Top actor: Boman Irani (25 titles)
   - Top director: Raúl Campos (20 titles)

✅ **5. Rating Patterns**
   - 91.8% of titles have IMDB scores
   - Average IMDB: 6.51/10
   - Highest rated: #ABtalks (9.6/10)

✅ **6. Movie vs TV Show Analysis**
   - Movies: 3,744 (64%)
   - Shows: 2,106 (36%)
   - Avg movie runtime: 102 minutes
   - Avg show seasons: 1.5

---

## 🚀 **How to Use This Project**

### **OPTION 1: Google Colab (Easiest - Recommended)**

#### Step 1: Open Google Colab
1. Go to: https://colab.research.google.com/
2. Click **"File" → "Upload notebook"**
3. Upload: `Netflix_Content_Explorer_Complete.ipynb`

#### Step 2: Upload Your Data
1. Click the **folder icon** 📁 on the left
2. Click **upload** icon ⬆️
3. Upload both:
   - `titles.csv`
   - `credits.csv`

#### Step 3: Run Everything
1. Click **"Runtime" → "Run all"**
2. Wait 2-3 minutes
3. See all results, charts, insights!

#### Step 4: Save Your Work
- Click **"File" → "Save a copy in Drive"**
- Your analysis is now saved!

---

### **OPTION 2: Run Python Script Locally**

```bash
# Prerequisites: Python 3.8+ installed

# Step 1: Install required packages
pip install pandas numpy matplotlib seaborn

# Step 2: Place files in same folder
# - netflix_complete_analysis.py
# - titles.csv
# - credits.csv

# Step 3: Run the script
python netflix_complete_analysis.py

# Results: 8 PNG visualizations generated!
```

---

### **OPTION 3: View Visualizations Only**

Simply open the PNG files - no coding required!
- Double-click any `.png` file
- View professional charts
- Perfect for presentations

---

## 📈 **Key Findings**

### 🎬 **Content Distribution**
- **Movies dominate**: 64% of content
- **TV shows**: 36% of content
- **2:1 movie-to-show ratio**

### 📅 **Temporal Insights**
- **Median release year**: 2018
- **90% from 2000+**: Focus on modern content
- **Peak decade**: 2010s with 56.5% of all content

### 🎭 **Genre Insights**
- **Top 3**: Drama (50.7%), Comedy (39.7%), Thriller (21.0%)
- **19 unique genres** total
- **Drama dominates** both movies and shows

### 🌍 **Geographic Diversity**
- **109 countries** producing content
- **US leads**: 39.7% of all content
- **India strong 2nd**: 10.6% of content
- **Asian presence**: Japan, South Korea, China well-represented

### ⭐ **Quality Metrics**
- **Average IMDB**: 6.51/10
- **91.8% have ratings** - strong data coverage
- **Top rated shows**: Breaking Bad (9.5), Avatar TLA (9.3)

### 🎬 **Top Talent**
- **51K+ actors** in database
- **3K+ directors** represented
- **Bollywood strong**: Boman Irani, Shah Rukh Khan, Kareena Kapoor
- **Global directors**: Raúl Campos, Martin Scorsese, Anurag Kashyap

### ⏱️ **Duration Patterns**
- **Avg movie**: 102 minutes (~1h 42min)
- **Avg show**: 1.5 seasons
- **Runtime range**: 1-320 minutes for movies

---

## 📋 **Dataset Schema**

### **titles.csv** (5,850 records)
| Column | Description |
|--------|-------------|
| id | Unique identifier |
| title | Content title |
| type | MOVIE or SHOW |
| description | Synopsis |
| release_year | Year released |
| age_certification | Rating (R, PG-13, TV-MA, etc.) |
| runtime | Minutes (movies) |
| genres | List of genres |
| production_countries | Countries produced |
| seasons | Number of seasons (shows) |
| imdb_id | IMDB identifier |
| imdb_score | IMDB rating (0-10) |
| imdb_votes | Number of IMDB votes |
| tmdb_popularity | TMDB popularity score |
| tmdb_score | TMDB rating |

### **credits.csv** (77,801 records)
| Column | Description |
|--------|-------------|
| person_id | Person identifier |
| id | Title identifier (links to titles.csv) |
| name | Actor/Director name |
| character | Character name (for actors) |
| role | ACTOR or DIRECTOR |

---

## 💡 **Use Cases**

### 📊 **For Data Science Students**
- Learn EDA techniques
- Practice data visualization
- Study real-world dataset

### 💼 **For Business Analysts**
- Content strategy insights
- Market analysis
- Competitive intelligence

### 🎓 **For Academic Projects**
- Complete portfolio piece
- Publication-ready charts
- Reproducible research

### 🎬 **For Entertainment Industry**
- Content trend analysis
- Talent scouting data
- Production insights

---

## 🔧 **Customization Ideas**

### **Analyze Specific Actor**
```python
# In Google Colab, add this cell:
actor_name = "Shah Rukh Khan"  # Change this
actor_titles = credits[credits['name'] == actor_name].merge(titles, on='id')
print(f"{actor_name} has {len(actor_titles)} titles")
print(actor_titles[['title', 'release_year', 'imdb_score']])
```

### **Filter by Genre**
```python
# Get only action movies
action_titles = titles[titles['genres_list'].apply(lambda x: 'action' in [g.lower() for g in x])]
print(f"Action titles: {len(action_titles)}")
```

### **Top Rated by Country**
```python
# Best US content
us_titles = titles[titles['countries_list'].apply(lambda x: 'US' in x)]
top_us = us_titles.nlargest(10, 'imdb_score')[['title', 'imdb_score']]
print(top_us)
```

---

## 📚 **Technologies Used**

- **Python 3.8+**
- **pandas** - Data manipulation
- **numpy** - Numerical operations
- **matplotlib** - Visualizations
- **seaborn** - Statistical plots
- **Jupyter** - Interactive notebooks

---

## 🎓 **Learning Outcomes**

By exploring this project, you'll learn:

✅ Data loading and cleaning
✅ Handling list-type columns
✅ Merging multiple datasets
✅ Creating professional visualizations
✅ Statistical analysis techniques
✅ Insight generation from data
✅ Report creation and documentation

---

## 📞 **Project Stats**

**Data Coverage:**
- 📊 5,850 titles analyzed
- 👥 77,801 cast/crew records
- 🌍 109 countries
- 🎭 19 genres
- ⭐ 5,368 IMDB ratings
- 📅 77 years (1945-2022)

**Analysis Outputs:**
- 🖼️ 8 visualizations
- 📓 1 Jupyter notebook
- 🐍 1 Python script
- 📄 Comprehensive documentation

---

## 🌟 **Next Steps**

### **For Beginners:**
1. ✅ Open visualizations (PNG files)
2. ✅ Read this README
3. ✅ Try Google Colab notebook

### **For Intermediate:**
1. ✅ Run Python script locally
2. ✅ Modify analysis parameters
3. ✅ Create custom visualizations

### **For Advanced:**
1. ✅ Build predictive models
2. ✅ Create recommendation system
3. ✅ Deploy as web application

---

## 📝 **Citation**

If you use this project, please cite:

```
Netflix Content Explorer - Exploratory Data Analysis
Dataset: Real Netflix Titles & Credits (5,850 titles, 77,801 credits)
Analysis Date: February 2026
```

---

## 🎉 **You're All Set!**

**Everything is ready to use:**
✅ Jupyter Notebook for Google Colab  
✅ Python script for local analysis  
✅ 8 professional visualizations  
✅ Complete documentation  
✅ Real Netflix data  

**Start exploring Netflix content insights today!** 🚀📊🎬

---

**Questions? Issues?**
- Check the Jupyter notebook for step-by-step code
- Review PNG visualizations for quick insights
- Run Python script for fresh analysis

**Happy Analyzing!** 🎉
