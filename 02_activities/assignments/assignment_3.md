# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
  The data visualizations were created using two different software tools: Tableau Public and Python. Tableau Public was used to develop an interactive visualization that allows users to explore patterns through filtering and dynamic interaction. Python, using the pandas and matplotlib libraries, was used to create a static, code-based visualization that emphasizes transparency, reproducibility, and precise control over data processing and plotting.
    
    > Who is your intended audience? 
The intended audience for both visualizations is the general public, including individuals without technical or programming backgrounds. The Tableau visualization is particularly well suited for this audience due to its intuitive interface and interactive features, which allow users to explore the data without needing prior analytical experience. The Python visualization, while also accessible, is especially useful for students, researchers, or technically inclined audiences who are interested in understanding or reproducing the analytical workflow.
    
    > What information or message are you trying to convey with your visualization? 
The primary message conveyed by both visualizations is how the volume of Toronto 311 service requests changes over time during 2025. By presenting daily counts of service requests, the visualizations highlight short-term fluctuations as well as broader temporal patterns that may reflect seasonal effects, changes in civic activity, or variations in public service demand. This time-based perspective helps viewers better understand how residents interact with municipal services over the course of the year.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
Several key design principles were considered in the creation of both visualizations, including clarity, simplicity, consistency, and readability. In Tableau, a clean line chart was used with minimal visual clutter, relying on default formatting and spacing to enhance legibility. In Python, the design focused on a straightforward line plot with clearly labeled axes, an informative title, and rotated x-axis labels to prevent overlap. In both cases, consistent scales and date formatting were applied to ensure accurate interpretation of trends.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
Reproducibility was addressed differently in each tool. The Python visualization is fully reproducible because the entire workflow, from data loading and cleaning to aggregation and plotting—is explicitly defined in code. Anyone with access to the dataset and the script can recreate the visualization exactly. Tableau Public offers partial reproducibility; while the visualization and underlying data can be shared publicly, the exact analytical steps are not as transparent as a scripted approach, which limits full reproducibility but still allows users to interact with and explore the results.
    
    > How did you ensure that your data visualization is accessible?  
Accessibility was an important consideration in both visualizations. Simple, high-contrast color choices were used to accommodate viewers with color vision deficiencies, and clear titles and axis labels were included to ensure the visualizations are understandable without additional explanation. Tableau enhances accessibility through interactive features such as tooltips and zooming, while the Python visualization maintains accessibility by avoiding complex visual encodings and presenting the data in a clear and familiar line chart format.
    
    > Who are the individuals and communities who might be impacted by your visualization?  
The individuals and communities potentially impacted by these visualizations include Toronto residents interested in civic issues, city planners and policymakers monitoring service demand, journalists examining municipal performance, and researchers or students studying urban data. By making trends in 311 service requests visible, the visualizations can support informed discussions about public service usage and resource allocation.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
The selection of dataset features was guided by relevance and clarity. The Creation Date variable was included because it directly supports temporal analysis, which was the focus of the visualization. Other variables, such as service type or geographic location, were excluded to avoid overcrowding the visual and to maintain a clear narrative. Rows with missing or invalid dates were removed to ensure accuracy and consistency in the time series displayed in both tools.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
Finally, substantial “underwater labour” contributed to the creation of the final visualizations. This included troubleshooting file path and CSV parsing errors, handling character encoding issues, cleaning and validating date fields, deciding on appropriate temporal aggregation, and iterating on design choices. Although much of this work is not visible in the final outputs, it was essential to producing accurate, reliable, and interpretable visualizations.
    
- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 02/02/2026`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
