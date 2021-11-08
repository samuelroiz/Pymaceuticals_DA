# Pymaceuticals_DA

## Background 

The company, Pymaceuticals, specializes in anti-cancer pharmaceuticals. It is a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals company started screening for potential treatments for squamous cell carcinoma (SCC). It is known as a form of skin cancer. Analyze the company with its given data to the complete data from their most recent animal study. In the data, there are 249 mice identified with SCC tumor growth. The mice were treated through a variety of drug regimens. Over 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. Generate all of the tables and figures needed for the technical report of the study. Create a top-level summary of the study results.

## Table's 

### Summary Stats Table
![Summary Stats Table](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Summary_Stat_Table.png)

This table portrays the Mouse ID along with its Tumor Volume. The Tumor Volume is calculated as the mean, median, variance, standard deviation, and others. It shows that each mouse tumor increases by 15 on average from the beginning to the end. However, this table helps understand which drug is beneficial or positive. 

## Chart's

Note: Values are found at timepoint 45

### Capomulin Drug

![Capomulin Drug](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Capomulin_Drug.png)

In this chart with a timepoint of 45, twenty-one mice used the Capomulin Drug for their tumor. Its final timepoint portrays the Capomulin Drug has increased its tumor at least above 30 mm3. Its maximum is almost 50 mm3. The minimum is at least 30 mm3. The average tumor is around 40 mm3 when using the Capomulin Drug.

### Ramicane Drug

![Ramicane Drug](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Ramicane_Drug.png)

In this chart with a timepoint of 45, twenty mice used the Ramicane Drug for their tumor. Its final timepoint portrays the Ramicane Drug has increased its tumor at least above 20 mm3. Its maximum is almost 47 mm3. The minimum is at least 20 mm3. The average tumor is around 36 mm3 when using the Ramicane Drug. Ramicane drug is efficient at reducing the tumor volume over time than the Capomulin drug. 

### Infubinol Drug

![Infubinol Drug](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Infubinol_Drug.png)

In this chart with a timepoint of 45, nine mice used the Infubinol Drug for their tumor. Its final timepoint portrays the Infubinol Drug has increased its tumor at least above 60 mm3. Its maximum is almost 67 mm3. The minimum is at least 60 mm3. The average tumor is around 64 mm3 when using the Infubinol Drug. Infubinol drug is less efficient at reducing the tumor volume over time than the Capomulin and Ramicane drug. It did the opposite of Ramicane, increasing the tumor size at a faster rate. 

### Ceftamin Drug

![Ceftamin Drug](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Ceftamin_Drug.png)

In this chart with a time point of 45, thirteen mice used the Ceftamin Drug for their tumor. Its final timepoint portrays the Ceftamin Drug has increased its tumor at least above 60 mm3. Its maximum is almost 67 mm3. The minimum is at least 60 mm3. The average tumor is around 62 mm3 when using the Ceftamin Drug. Ceftamin drug is less efficient at reducing the tumor volume over time than the Capomulin and Ramicane drug. It did the opposite of Ramicane, increasing the tumor size at a faster rate. Therefore, the Ceftamin had the same results as the Infubinol drug.  

### Four drug's chart combined together

![All Four Drug's](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Four_Drugs_Tot_pyplot_bar.png)

### All Drugs Chart

![All Nine Drug's](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Drugs_Total_Timepoint_pyplot_bar.png)

This chart portrays the nine drugs used in the data and the outcome of the number of time points. The sum of timepoints shows what drug kept the mice's life span longer. Those two drugs with the highest sum of timepoints are Placebo and Infubinol. The lowest sum of timepoints is Propiva. The higher the sum timepoints are, the drug will keep the mice live longer and reduce the rate of the tumor. The lower the sum timepoints are, the drug poorly reduces the rate of tumor growth.  

## Pie Chart

### Gender Total 

![Gender Total](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Gender_Tot_pyplot_pie.png)

The pie chart displays the percentage of females versus males in the given data. There is point two percent more male mice than females. It tells us that the data can be used as a gender versus male in comparisons to see if gender plays a role in the data. 

### Gender Total of Studies 

![Total of Studies Female v Male](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Total_Studies_pandas_pie.png)

It shows the number of mice that survived evenly at time points. It also displays gender does not play a role in drug and tumor growth rate. 

