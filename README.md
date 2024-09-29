# BREAST-CANCER-CLASSIFICATION-USING-ML
Breast cancer is one of the most common cancers affecting women worldwide. Early detection is crucial for effective treatment and improved survival rates. This project aims to develop a machine learning model to predict whether a breast cancer tumor is malignant or benign using various features of the tumor.

## Pie Chart of Tumor Stages
<img width="758" alt="Screenshot 2024-09-29 at 2 33 38 AM" src="https://github.com/user-attachments/assets/c98ffdb3-6262-4de3-848a-81c1eee4fa77">

In this step, we created scatter plots to visualize the relationship between the age of patients and their tumor
size, categorized by their status ('Alive' or 'Dead'). The plots are enhanced with a regression line to show the
trend.
Data Filtering:
• The dataset was split into two subsets: one for 'Alive' patients and another for 'Dead' patients.
Conditional Plotting:
• With 'Node Count':
• For both 'Alive' and 'Dead' patients, scatter plots were created with 'Age' on the x-axis and 'Tumor Size'
on the y-axis. The point sizes represented 'Node Count', and a regression line was added to indicate the
trend. Outliers (Tumor Size > 40 and Age < 30) were annotated.
• Without 'Node Count':
• Similar scatter plots were generated without sizing the points by 'Node Count'.
Plot Details:
• Each plot is sized at 12x8 inches.
• Axes are labeled appropriately.
• The plot title indicates the patient status being visualized.
• Legends are positioned outside the plot area for clarity.
• These visualizations provide insights into the relationship between age and tumor size, highlighting trends and
significant outliers in the data.


## Count Plot: Tumor Size by Tumor Stage:
<img width="528" alt="image" src="https://github.com/user-attachments/assets/832a0472-a27c-43a1-b276-076a13de5a96">

In this step, we created a count plot using Seaborn to visualize the distribution of marital statuses in the dataset and
their corresponding survival rates. The plot shows the counts of each 'Marital Status' category, with color-coding to
represent survival status ('Status'). The plot was generated using sns.countplot, with a 'Set1' color palette to
differentiate between survival statuses. Labels for the x-axis and y-axis were added for clarity, along with a plot title to
indicate the relationship being explored. The legend was customized to include a title, making it clear what the colors
represent. For better readability, the x-axis labels were rotated by 45 degrees. This plot provides insights into how
different marital statuses relate to survival rates, highlighting potential patterns or trends in the dataset.


