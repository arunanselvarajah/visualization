# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    Tableau Public and Python were used. THe python code is in the notes file (at the end). 
    
    > Who is your intended audience? 
    The intended audience for this visualization is the general public, including Toronto residents, community advocates, and individuals interested in understanding how municipal services are used across the city. The visualization is designed to be interpretable without prior technical or statistical knowledge.    

    > What information or message are you trying to convey with your visualization? 
    The visualization communicates how 311 service requests are distributed across Toronto wards, highlighting which areas generate the highest volume of requests. This helps illustrate patterns in service demand and may reflect differences in population density, infrastructure needs, or access to municipal services across the city.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    Several design principles were considered, including clarity, simplicity, and visual hierarchy. A horizontal bar chart was used to improve readability of ward labels, and the data were sorted in descending order to make comparisons intuitive. A single, high-contrast colour was selected to avoid visual clutter and to support accessibility. Clear axis labels and a descriptive title were included to ensure the visualization can be understood without additional context.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    While Tableau Public is not fully reproducible in the same way as code-based tools, reproducibility was supported by using a publicly available dataset and relying on transparent, built-in aggregations (e.g., counts of records by ward). The original dataset and the visualization settings can be accessed and reviewed through Tableau Public, allowing others to recreate or adapt the visualization. However, changes to the dataset or software interface may require manual reconfiguration of the visualization.

    > How did you ensure that your data visualization is accessible?  
    Accessibility was considered by using a colour-blind friendly palette, avoiding red–green contrasts, and ensuring sufficient contrast between bars and background elements. Labels, titles, and axes were written in plain language and sized appropriately for readability. The visualization avoids unnecessary decoration, reducing cognitive load for viewers.

    > Who are the individuals and communities who might be impacted by your visualization?  
    Communities living in wards with higher volumes of 311 service requests may be impacted by the issues represented in the data, such as infrastructure concerns, noise complaints, or public safety issues. City staff, policymakers, and community organizations may also use this information to better understand service demand and support more equitable resource allocation.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    The visualization focuses on the ward variable and the count of service requests to emphasize geographic differences in service usage. Other variables, such as intersection street names or internal divisions, were excluded because they introduce unnecessary complexity and do not contribute directly to the high-level message intended for a general audience.

    > What ‘underwater labour’ contributed to your final data visualization product?
    Significant unseen work contributed to the final visualization, including reviewing the dataset for missing or inconsistent values, addressing text encoding issues, verifying that dates and categorical variables were correctly interpreted by Tableau, and experimenting with multiple chart types before selecting the most effective design. This preparatory work was essential to ensure accuracy, clarity, and interpretability.

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
