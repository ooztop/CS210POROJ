# Step Count and Music Listening Behavior Analysis

### 1. Dataset Description

#### **Step Count Data**
- **Source**: Apple Health step count records.
- **Scope**: Daily step counts and timestamps.

**Details**:
- Total steps taken each day, serving as a proxy for outdoor activity or physical movement.

#### **Spotify Listening Data**
- **Source**: Spotify API.
- **Scope**: Spotify listening history.

**Details**:
- The total number of songs listened to daily.
- Listening duration in minutes.
- Song features such as energy, danceability, and mood metrics.

---

### 2. Project Idea

This project seeks to analyze daily step counts to estimate time spent outside or engaged in physical activity and investigate how this correlates with Spotify listening behavior. The goal is to uncover potential patterns between physical activity, outdoor movement, and music listening preferences.

**Key Research Questions**:
1. Can daily step counts serve as a reliable indicator of the time spent outdoors or physical activity levels?
2. As physical activity increases, how do Spotify listening habits (e.g., listening duration, genre preferences) change?

---

### 3. Project Plan

#### **Phase 1: Data Collection**

- **Step Count Data**:
  - Extract daily totals and timestamps from Apple Health step count data.

- **Spotify Data**:
  - Use Spotify API to collect listening history, including listening duration, song count, and audio features.
  - Securely manage API tokens.

---

#### **Phase 2: Data Preprocessing**

- **Merge datasets**:
  - Align Apple Health step count data with Spotify listening data based on matching date fields.

- **Data Cleaning**:
  - Handle missing or inconsistent records in both datasets.
  - Normalize step count and music listening metrics for analysis.

---

#### **Phase 3: Analysis and Modeling**

- **Relationship Analysis**:
  - Explore correlations between daily step counts and estimated time spent outdoors.
  
- **Behavioral Modeling**:
  - Develop a model to predict physical activity levels based on step count metrics.
  - Analyze how increased step counts influence music listening patterns (e.g., genres, energy levels, listening duration).

- **Visualization**:
  - Create graphs to illustrate key trends, such as step counts vs. listening time or genre preferences at different activity levels.

---

#### **Phase 4: Findings and Deliverables**

- **Visual Reports**:
  - Generate clear visualizations showing the relationships between step counts, activity levels, and music behavior.

---

### **Expected Outcomes**

- Identification of step counts as a potential proxy for outdoor time or physical activity levels.
- Insights into how increased physical activity impacts music listening behaviors, such as duration, genre, or energy level.

---

