# Exploring_gendergap_STEM_using_pandas_matplotlib_seaborn



The Department of Education Statistics releases a data set annually containing the percentage of bachelor's degrees granted to women from 1970 to 2012. The data set is broken up into 17 categories of degrees, with each column as a separate category.

Randal Olson, a data scientist at University of Pennsylvania, has cleaned the data set and made it available on his personal website.

Research questions are:
Is there a gap between women and men in the STEM fields? The stem fields are 'Engineering', 'Computer Science', 'Psychology', 'Biology', 'Physical Sciences', and 'Math and Statistics'.
Is there a gap between women and men in the non STEM fields?

The research questions are in the first steps answered with explorative data analysis using data visualizations. The visualizations are made by reducing the Data-Ink Ratio.

In the second step data analysis with pandas is done in particular using "groupby" to distinguish between men and women. Data analysis pandas needs a data frame as basic structure. In the first step such a data frame is created including both women and men values. A variable "Gender" distinguishes then between "man" and "women."
