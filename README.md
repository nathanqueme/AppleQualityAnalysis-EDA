# UTS Assessment Task 2: Data Exploration and Preparation

**Grade:** HD (Full Marks)  

This project, worth 35% of the total grade, focused on exploring and preparing data to analyze apple quality based on various attributes. Visual **EDA** and data preprocessing were central to gaining insights.

### Key Steps:
1. **Visual EDA**: 
   - Explored relationships between apple attributes (size, weight, juiciness, etc.) with various charts and scatter plots.
   - Identified outliers using IQR and visualized attribute distributions.
   - Correlation heatmaps highlighted key relationships, especially between juiciness, acidity, and quality.
   
2. **Data Preprocessing**:
   - **Binning**: Applied equi-width and equi-depth binning for size.
   - **Normalization**: Used min-max and z-score normalization for sweetness.
   - **Discretization**: Converted juiciness into three categories: mild, medium, and extreme.
   - **Binarization**: Transformed the nominal quality variable ("good" or "bad") into numerical form for analysis.

3. **Insights**:
   - **Juiciness** strongly influenced apple quality, with good apples having higher juiciness levels.
   - Smaller, sweeter apples with low acidity were typically higher quality.
   - K-means clustering revealed two main clusters: high-quality apples with higher juiciness and lower acidity, and lower-quality apples with opposite traits.

Check the repository for visualizations and detailed analysis!
