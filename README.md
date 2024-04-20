# Pymaceuticals_DA

## Background

Pymaceuticals is a burgeoning pharmaceutical company based in San Diego that specializes in anti-cancer pharmaceuticals. The company has started screening for potential treatments for squamous cell carcinoma (SCC), a form of skin cancer. Analyze the complete data from their most recent animal study, which includes observations on 249 mice identified with SCC tumor growth. The mice were treated with a variety of drug regimens, and over 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, with other treatment regimens. Generate all of the tables and figures needed for the technical report of the study and create a top-level summary of the study results.

## Tables

### Summary Stats Table
![Summary Stats Table](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Summary_Stat_Table.png)

This table portrays the Mouse ID along with its Tumor Volume. The Tumor Volume is calculated as the mean, median, variance, standard deviation, and more. It shows that each mouse's tumor increases by 15 on average from the beginning to the end. However, this table helps understand which drug is beneficial.

## Charts

Note: Values are found at timepoint 45.

### Capomulin Drug

![Capomulin Drug](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Capomulin_Drug.png)

In this chart with a timepoint of 45, twenty-one mice used the Capomulin Drug for their tumor. Its final timepoint portrays that the Capomulin Drug increased the tumor size to at least above 30 mm3, with a maximum of almost 50 mm3 and a minimum of at least 30 mm3. The average tumor size is around 40 mm3 when using the Capomulin Drug.

### Ramicane Drug

![Ramicane Drug](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Ramicane_Drug.png)

In this chart with a timepoint of 45, twenty mice used the Ramicane Drug for their tumor. Its final timepoint portrays that the Ramicane Drug increased the tumor size to at least above 20 mm3, with a maximum of almost 47 mm3 and a minimum of at least 20 mm3. The average tumor size is around 36 mm3 when using the Ramicane Drug. Ramicane is more efficient at reducing tumor volume over time than the Capomulin drug.

### Infubinol Drug

![Infubinol Drug](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Infubinol_Drug.png)

In this chart with a timepoint of 45, nine mice used the Infubinol Drug for their tumor. Its final timepoint portrays that the Infubinol Drug increased the tumor size to at least above 60 mm3, with a maximum of almost 67 mm3 and a minimum of at least 60 mm3. The average tumor size is around 64 mm3 when using the Infubinol Drug. Infubinol is less efficient at reducing tumor volume over time compared to the Capomulin and Ramicane drugs, actually increasing the tumor size at a faster rate.

### Ceftamin Drug

![Ceftamin Drug](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Ceftamin_Drug.png)

In this chart with a timepoint of 45, thirteen mice used the Ceftamin Drug for their tumor. Its final timepoint portrays that the Ceftamin Drug increased the tumor size to at least above 60 mm3, with a maximum of almost 67 mm3 and a minimum of at least 60 mm3. The average tumor size is around 62 mm3 when using the Ceftamin Drug. Ceftamin is less efficient at reducing tumor volume over time compared to the Capomulin and Ramicane drugs, showing the same results as the Infubinol drug.

### Four Drugs Chart Combined Together

![All Four Drugs](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Four_Drugs_Tot_pyplot_bar.png)

### All Drugs Chart

![All Nine Drugs](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Drugs_Total_Timepoint_pyplot_bar.png)

This chart portrays the nine drugs used in the data and the outcome of the number of timepoints. The sum of timepoints shows which drug kept the mice's lifespan longer. The two drugs with the highest sum of timepoints are Placebo and Infubinol. The lowest sum of timepoints is Propiva. The higher the sum of

 timepoints, the longer the drug will keep the mice alive and reduce the rate of the tumor. The lower the sum of timepoints, the poorer the drug is at reducing the rate of tumor growth.

### Four Drugs

![Four Drugs](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/FourDrugBoxPlot.png)

The following image is a chart that displays the final tumor volume of the four chosen treatments: Capomulin, Ramicane, Infubinol, and Ceftamin. Capomulin and Ramicane have a higher success rate in reducing the tumor than Ceftamin and Infubinol.

## Pie Chart

### Gender Total

![Gender Total](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Gender_Tot_pyplot_pie.png)

The pie chart displays the percentage of females versus males in the given data. There is a 0.2 percent more male mice than females. It indicates that the data can be used as a gender versus male comparison to see if gender plays a role in the data.

### Gender Total of Studies & Tumor Vol.

![Total of Studies Female vs Male](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Total_Studies_pandas_pie.png)

![Total of Tumor Volume Female vs Male](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Gender_Avg_Tumor_pyplot_pie.png)

The charts show the number of mice that survived evenly at timepoints. It also displays that gender does not play a significant role in drug efficacy and tumor growth rate.

### Capomulin Drug Charts

![Scatter Plot Weight Vs Tumor Vol](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Scatter_Plot_Weight_Vs_TumorVol_WITH_REG.png)

The following image displays the weight versus tumor volume of using the Capomulin drug only. It also includes the regression equation to help the readers understand the correlation between the two variables.

![Line Chart Weight Vs Tumor Vol](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Capomulin_Line_Chart_Plot.png)

The image portrays the timepoints of mice that used the Capomulin drug. The y-values are calculated as the mean. We see that the tumor volume is reduced dramatically as each day goes by.

## Search Code

### Mouse Searched Output

![Mouse: a203](https://github.com/samuelroiz/Pymaceuticals_DA/blob/main/Images/Output_Search_MouseID.png)

The following image displays the outcome of the code when you search for a mouse. You are shown a list of mouse IDs, then you are asked to search up one of the following mouse's ids. If not entered one of the mouse ids above, then the code fails. If entered one of the mouse ids above, then the code will run. As it runs, it will display a table of its mouse id, drug regimen, sex, age, weight, a total of studies, timepoint total, tumor volume average, and the number of metastatic sites.

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/samuelroiz/1af49ec9eea365bc845ba04c5071a976) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

* **Samuel Roiz** - *Data clean, Analyzed Data, Math Model* - [Profile](https://github.com/samuelroiz)

See also the list of [contributors](https://github.com/samuelroiz) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://gist.github.com/samuelroiz/1af49ec9eea365bc845ba04c5071a976) file for details.

## Acknowledgments

* Pymaceuticals
* USC Data Visualization
* CSUN Mathematics
