# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    # Visualization 1: Incident Rate by Region (Toronto Police Data)
    # https://data.ontario.ca/dataset/police-reported-crime-rates-by-age/resource/84cf68aa-8c6c-487a-96bf-902ff00a0128
    I used Python with the Pandas and Matplotlib libraries to clean the dataset and create the bar chart visualization.
    
    > Who is your intended audience? 
    # Visualization 1:
    The intended audience includes Toronto residents, policymakers, journalists, and public safety researchers interested in understanding regional differences in crime.

    > What information or message are you trying to convey with your visualization? 
    # Visualization 1:
    The visualization highlights differences in incident rates across Toronto police regions. The goal is to show that crime reporting rates vary geographically and may require region-specific policy responses.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    # Visualization 1:
    I used a bar chart because it allows clear comparison between regions. The bars were sorted in descending order to make differences easier to interpret. Axis labels and titles were clearly defined to avoid ambiguity. I removed unnecessary visual clutter and used consistent formatting to maintain clarity and readability.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    # Visualization 1:
    All data cleaning and plotting steps were scripted in Python and included in the appendix. The dataset source is publicly available, and the file path is documented. Because the visualization is fully coded, it can be reproduced by anyone using the same dataset and script.

    > How did you ensure that your data visualization is accessible?  
    # Visualization 1:
    I used clear labeling to improve readability. The visualization does not rely solely on color to communicate meaning. Text sizes were kept large enough for visibility, and unnecessary elements were avoided.

    > Who are the individuals and communities who might be impacted by your visualization?  
    # Visualization 1
    Residents of regions with higher reported incident rates may be affected by public perception or policy changes. Community organizations and local policymakers may use this information to advocate for targeted resources or interventions.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    # Visualization 1:
    I selected the Incident Rate variable because it accounts for population differences between regions. I excluded other variables such as clearance rates and age-specific charges to maintain focus and avoid overcomplicating the visualization.

 
    > What ‘underwater labour’ contributed to your final data visualization product?
    # Visualization 1:
    I spent time cleaning column names, removing formatting inconsistencies, converting text-based numeric values, sorting data correctly, and testing different layout options. Ensuring correct file paths and reproducibility also required troubleshooting and validation.

  

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
* Submission Due Date: `23:59 - 11/02/2025`
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
