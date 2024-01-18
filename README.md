# youDrawIt-Study1
All the codes and project files to reproduce study 1 analysis from our paper **The Impact of Elicitation and Contrasting Narratives on Engagement, Recall and Attitude Change with News Articles Containing Data Visualization**

# The Impact of Elicitation and Contrasting Narratives on Engagement, Recall and Attitude Change with News Articles Containing Data Visualization
### Milad Rogha , Subham Sah, Alireza Karduni , Douglas Markant, and Wenwen Dou

### Abstract
News articles containing data visualizations play an important role in informing the public on issues ranging from public health to politics. 
Recent research on the persuasive appeal of data visualizations suggests that prior attitudes can be notoriously difficult to change. 
Inspired by an NYT article, we designed two experiments to evaluate the impact of elicitation and contrasting narratives on attitude change, recall, and engagement.
We hypothesized that eliciting prior beliefs leads to more elaborative thinking that ultimately results in higher attitude change, better recall, and engagement. Our findings revealed that visual elicitation leads to higher engagement in terms of feelings of surprise. While there is an overall attitude change across all experiment conditions, we did not observe a significant effect of belief elicitation on attitude change. With regard to recall error, while participants in the draw trend elicitation exhibited significantly lower recall error than participants in the categorize trend condition, we found no significant difference in recall error when comparing elicitation conditions to no elicitation. In a follow-up study, we added contrasting narratives with the purpose of making the main visualization (communicating data on the focal issue) appear strikingly different. Compared to the results of study 1, we found that contrasting narratives improved engagement in terms of surprise and interest but interestingly resulted in higher recall error and no significant change in attitude. We discuss the effects of elicitation and contrasting narratives in the context of topic involvement and the strengths of temporal trends encoded in the data visualization.


Please find the pre-print here: [Link to the pre-print](https://arxiv.org/abs/2401.05511)


## Replicability Instructions
In order to reproduce the analysis for **Study 1** depicted in the paper, please follow the steps below. Here we provide a step-by-step instructions to reproduce the analysis for **Study 1** in the paper (Figure 8.)

### 1. Install R and R Studio
All analyses were conducted in R version 4.2.3. Download and Install R and R Studio from [RStudio Desktop](https://posit.co/download/rstudio-desktop/) .

### 2. Load the Project file
In the R studio, go to file \-> Open project... \-> 
select and open the file `Data and Analysis.Rproj` from `1_analysis_and_results/R_and_Py/Data and Analysis.Rproj`
YOu do not need to run the rest of the scripts. They will be running inside the mentioned scripts.

### 3. Install required packages
After loading the project, in the `files` section, run `packages.R`. This script installs the required packages on your system.

**Note**: When opening each script, there may be packages missing. In such cases, a notification appears on the top of the screen, prompting to install the missing packages. Simply click on the Install missing packages link, and the program will automatically download the missing packages.

For more information regarding the packages and environment settings used by the authors, please look at the [Session_info](./Session_info.md).


### 3. Run the script

Scripts are located in `1_analysis_and_results/R_and_Py/analysis/`
Run `trendelicitation_study1.R`.

### 4. Plots
After running the script, the results (outputs) can be seen in the console log, and plots appear in their respective window in R Studio as well as [results_figures](./results_figures/). Results tables are located in [results_tables](./results_tables/).

You can check your outcomes with the results of the **Study 1** in the paper.


## Reproduce all analysis (Study 1 & Study 2 & Combined)
To reproduce the results of **Study 2** and **Combined** analysis, please visit [our paper's repository on GitHub](https://bit.ly/48Bxz2D).
