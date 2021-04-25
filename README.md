# Gapminder Animated Scatterplot
**In this project I've tried to apply what I've learned during first week:**
## 1. Reading 'csv' and 'excel' files into Pandas Frame
 - `pd.read_csv()`, `pd.read_excel()`
## 2. Data wrangling and cleaning
 - Accessing columns and index in DataFrame and their Manipulation
    - `df.columns`, `df.index(.name)` , `df.reset_index()`
 - Formatting Wide-Long
    -  `df.melt()`
 - Merge tables
    - `df.merge(df2_to_be_merged_into_df)`
## 3. Data Visualisation
 - Seaborn - Matplotlib
    - `sns.lineplot()' , 'sns.scatterplot()`
 ![](./pictures/1960.png)
 - Annotation
    - `plt.annotate()`
 - Creating .gif
    - imageio library `import imageio`
 ![](./animated_scatterplot.gif)