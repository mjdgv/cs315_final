# cs315_final
**Authors**: Sazma Sarwar, Lucia Gurrieri, Mary Jo del Granado, Lillie Godinez, Amy Hu

**Research questions**:  
1. To what extent are advertisements on TikTok directed to user preferences? How do advertisements differ from non-advertising content?
2. Given our sample of data donations from Wellesley College students, aged 18-24, how are advertisements tailored to this specific user demographic?

**Methods**:  
- clustering  
- divergence  
- topic modeling

## The data
**Folder**: pyktok_data  
**Purpose**: holds the pyktok results csv files of 19 different users.  

**Folder**: aggregated_data  
**Items**:
- visualizations  
  - folder with images of data description figures
- all_videos.csv
  - pyktok results of 19 users combined  
- all_ads.csv
  - pyktok results of 19 users combined filtered by ads
- all_nonads.csv
  - pyktok results of 19 users combined filtered by nonads

## The methods
**Folder**: divergence
**Items**:
- divergence.ipynb
  - documented python notebook with code for the divergence analysis
- data
  - folder with the pyktok results files for 5 users
 
**File**: clustering_multiple_accounts.ipynb  
**Purpose**: documented python notebook with code for the clustering analysis and a comparison of results using Dunn index

**File**: topic-modeling-ads.ipynb  
**Purpose**: documented python notebook with code for the LDA-based topic modeling analysis using _all_videos.csv_ from aggregated_data folder

**File**: DataExploration.ipynb  
**Purpose**: documented python notebook with code for initial data exploration of csv files in aggregated_data folder. 
