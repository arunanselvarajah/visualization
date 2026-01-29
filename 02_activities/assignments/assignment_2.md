# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      Visualization: “Life Expectancy vs Income” bubble chart from Gapminder
        Link: Gapminder World Health Chart – bubbles of life expectancy vs income: https://www.gapminder.org/fw/world-health-chart/?utm_source
               
        The Gapminder bubble chart, popularized by Hans Rosling, is widely considered a strong example of effective visual communication. It displays three quantitative variables simultaneously: life expectancy on the vertical axis, income per             capita on the horizontal axis, and population size through bubble size, with continent/region mapped to colour. This allows readers to perceive multiple dimensions at once without cognitive overload, a key design principle in data                 visualization scholarship.
        
        First, the chart type fits the data and message: a bubble scatterplot clearly shows relationships and clustering among countries. Scatter plots are recommended when exploring correlations between continuous variables because they allow             accurate perception of position on common scales, which is one of the most perceptually effective visual encodings. (Cleveland & McGill, 1984).
        
        Second, colour and size are used meaningfully. Colour distinguishes regions (e.g., Africa, Europe), which helps viewers see geographic patterns; bubble size indicates population, adding deeper context to interpretations without                     overwhelming the viewer. Labels and axes are clear, and interactive versions let users filter by year or region, enhancing usability.
        
        Third, the chart tells a story. Over time (in the interactive version), one can see how countries move across the chart in the past two centuries, illustrating global development trends. This narrative feature supports analytic insight             beyond static numbers. (Knaflic, Storytelling with Data, 2020).

      Visualization: “Show Pie Chart for Customers as Top 10, Top 11–20 and Others”
        Platform: Tableau Public
        Link: https://public.tableau.com/app/profile/pownkumar/viz/ShowPieChartforCustomersasTop10Top11-20andOthers/Sheet2

      This Tableau Public visualization uses a pie chart to represent customer categories grouped into segments such as “Top 10,” “Top 11–20,” and “Others.” While pie charts are commonly used to display parts of a whole, this particular example         demonstrates several well-documented weaknesses in data visualization design, making it an ineffective and potentially misleading way to communicate the underlying data.
        
        First, the choice of chart type is inappropriate for accurate comparison. Pie charts require viewers to compare angles and areas, which are perceptually less precise than comparing lengths along a common scale. Research in graphical                 perception shows that humans are significantly better at judging position and length than angle or area, making pie charts a poor choice when the goal is to compare relative magnitudes between categories (Cleveland & McGill, 1984). In             this visualization, it is difficult to determine whether one customer segment is meaningfully larger than another, particularly when slices are similar in size.
        
        Second, the visualization suffers from cognitive overload due to colour and segmentation. Multiple slices are distinguished primarily by colour, but the palette does not follow a perceptually uniform or accessibility-aware scheme. This             makes it harder for viewers, particularly those with colour vision deficiencies, to distinguish between categories. Additionally, the grouping of customers into “Top 10,” “Top 11–20,” and “Others” lacks clear justification within the             visual itself, forcing viewers to infer meaning without sufficient contextual explanation. Tableau’s own visualization guidance cautions that pie charts become less effective as the number of categories increases and when distinctions             between slices are subtle.
        
        Third, the chart provides limited support for interpretation and storytelling. There are no direct data labels on the slices, requiring viewers to rely on legends or hover interactions. This increases cognitive effort and interrupts the             flow of interpretation. Effective data visualizations should minimize the mental work required to extract insights, yet this chart requires viewers to repeatedly shift attention between slices and legend to understand values. As Edward         Tufte emphasizes, visualizations should strive to maximize data clarity while minimizing non-essential visual burden.

        
      ```
    - How could this data visualization have been improved?  
      ```
           Visualization: “Life Expectancy vs Income” bubble chart from Gapminder
        Link: Gapminder World Health Chart – bubbles of life expectancy vs income: https://www.gapminder.org/fw/world-health-chart/?utm_source
        
      Although the Gapminder visualization is highly effective, several refinements could further improve its accessibility and interpretability. First, the default colour palette could be optimized to better support viewers with colour vision             deficiencies. While colour is used meaningfully to distinguish geographic regions, ensuring sufficient contrast and avoiding problematic red–green combinations would make the visualization more inclusive and align with accessibility             best practices in data visualization. Designing with colour-blind–safe palettes ensures that insights remain equally visible to all audiences without relying solely on hue differences.
        
        In addition, the visualization could benefit from the inclusion of brief, strategically placed annotations that highlight key historical events. Annotating major global disruptions—such as pandemics, economic crises, or periods of war—               would help contextualize abrupt changes or trends in life expectancy and income over time. These annotations would support viewers who may be less familiar with global history, strengthening the narrative dimension of the visualization         while maintaining clarity.

        Visualization: “Show Pie Chart for Customers as Top 10, Top 11–20 and Others”
                Platform: Tableau Public
                Link: https://public.tableau.com/app/profile/pownkumar/viz/ShowPieChartforCustomersasTop10Top11-20andOthers/Sheet2
        
        A more effective alternative would be to replace the pie chart with a two-dimensional bar chart. Bar charts allow viewers to compare values using length along a common baseline, which is perceptually more accurate and easier to interpret, especially when dealing with grouped categories. Sorting bars from largest to smallest would further enhance clarity by immediately revealing dominant customer segments.
        
        Additionally, the visualization could be improved by simplifying colour usage and enhancing accessibility. Using a limited, colour-blind–friendly palette with sufficient contrast would reduce visual clutter and improve inclusivity. Finally, directly labeling bars with exact values would eliminate the need for legends and reduce cognitive load, making the visualization clearer, more honest, and more effective as a communication tool.

        References
        
        Cleveland, W. S., & McGill, R. (1984). Graphical perception: Theory, experimentation, and application to the development of graphical methods. Journal of the American Statistical Association, 79(387), 531–554.                     https://doi.org/10.1080/01621459.1984.10478080
        
        Gapminder Foundation. (n.d.). Life expectancy vs. income (World Health Chart). Gapminder. https://www.gapminder.org/fw/world-health-chart/
        
        Knaflic, C. N. (2020). Storytelling with data: A data visualization guide for business professionals (2nd ed.). Wiley.
        
        Tableau. (n.d.). What is a pie chart? Tableau Software. https://www.tableau.com/chart/what-is-pie-chart
        
        Tableau Public. (n.d.). Show pie chart for customers as Top 10, Top 11–20 and Others [Data visualization]. Tableau Public. https://public.tableau.com/app/profile/pownkumar/viz/ShowPieChartforCustomersasTop10Top11-20andOthers/Sheet2
        
        Tufte, E. R. (2001). The visual display of quantitative information (2nd ed.). Graphics Press.
      
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 01/26/2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
