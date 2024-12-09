# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  

### Python Visualization

    > What software did you use to create your data visualization?

    Python

    > Who is your intended audience? 

    General public 
    
    > What information or message are you trying to convey with your visualization? 

    I wanted to highlight the top 10 wards with the highest number of registered short-term rental properties. This provides a clear picture of where short-term rental activity is most concentrated in Toronto.
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
    
    Design principles applied to the visualization

    Aesthetic (Pleasing to Look At): Chose a cyan color scheme with black text and white background for a clean, visually appealing design. additionally, used outlines on bars enhance clarity without clutter.

    Substantive (Accurate Data Presentation): Displayed the top 10 wards based on property count, ensuring an honest and clear data representation. Additionally, carefully placed gridlines and axis labels for accurate interpretation.

    Perceptual (Clear Message): Rotated x-axis labels to avoid overlap, ensuring ward names are easy to read and the message is clear.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
    Python data visualizations are reproducible and additionally, I ensured that my code was neat and included detailed comments of every step.

    > How did you ensure that your data visualization is accessible?

    I ensured that my visualization was accessible by using:

    Clarity and Simplicity: Focused on the top 10 wards with the most properties to present concise, easy-to-understand information. Additionally, rotated x-axis labels to prevent text overlap.

    Barrier-Free Presentation: i) Used a high-contrast color scheme: cyan bars, white background, and black fonts to improve readability,  ii) Added gridlines for better alignment and clarity, and iii) Enhanced bar outlines for clearer definition.

    Appropriate Text Design: Ensured labels, legends, and titles use clear, simple text and spacing to reduce cognitive load.
   
    > Who are the individuals and communities who might be impacted by your visualization?

    My visualization can impact i) Local residents, ii) Short-term rental operators, ii) City planners and policymakers, iii) Tourists and visitors, iv) Local businesses, v) Advocacy groups and housing organizations, and vi) Academic and research communities.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization?

    I chose dataset features for my visualization by focusing on showcasing the distribution of short-term rental properties across Toronto wards.

    Included Features: i) ward_name to identify wards, ii)Counts of properties grouped by ward_name to highlight the distribution, and iii) A filter for the top 10 wards to focus on the most impactful areas.

    Excluded Features: Details like operator_registration_number, unit, and address, as they are granular and irrelevant to ward-level insights.
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    The "underwater labor" includes cleaning and grouping the dataset, coding and debugging the visualization in Python, and ensuring design clarity with accessible colors and labels. Contextual research and thoughtful presentation make the insights accurate and impactful.

### Tableau Visualization

    > What software did you use to create your data visualization?

    Tableau

    > Who is your intended audience? 

    General public 
    
    > What information or message are you trying to convey with your visualization? 
    
    I aimed to illustrate the geographic distribution of short-term rental activity in Toronto, focusing on highlighting the postal codes with the highest concentration of short-term rental registrations.

    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    
    For my Tableau visualization, I applied:

    Substantive: Ensured accurate data representation by clearly labeling counts and focusing on 40 relevant postal codes.

    Perceptual: Used map-based plotting, proportional marker sizes, and labels to convey patterns clearly.

    Aesthetic: Balanced colors and marker sizes for a clean, engaging, and visually appealing design.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
    Tableau visualizations are not inherently reproducible. This lack of reproducibility limits verification, reduces transparency, and hinders collaboration. To mitigate this, I ensure detailed documentation and share all relevant resources.

    > How did you ensure that your data visualization is accessible?  
    
    I ensured accessibility in my Tableau visualization by designing it with clarity, simplicity, and inclusiveness in mind:

    Ease of Understanding: Selected and designed graph variables that are intuitive for the general public, avoiding excessive information to reduce cognitive workload.

    Visual Contrast: Used indigo data points against a grey map for high contrast, making the rental density visually distinct.

    Clear Annotations: Included labels, a title, a legend, and Alt-text in the caption to describe the visualization comprehensively and provide context for assistive technologies.

    These choices align with accessibility principles by making the visualization clear, predictable, and barrier-free for diverse audiences.

    > Who are the individuals and communities who might be impacted by your visualization?  
    
    My visualization can impact i) Local residents, ii) Short-Term rental operators, ii) City planners and policymakers, iii) Tourists and visitors, iv) Local Businesses, v) Advocacy groups and housing organizations, and vi) Academic and research communities.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
    I chose dataset features for my visualization by based on their relevance to geographic and density insights.

    Included Features: i) Longitude and Latitude to map the rentals spatially, ii) Postal Code to show localized concentration and trends, and iii) Count of Postal Code to represent the density of rentals visually.

    Excluded Features: Details like address, unit, or operator_registration_number, as they are too granular and not necessary for geographic insights.

    > What ‘underwater labour’ contributed to your final data visualization product?

    The underwater labor for the Tableau visualization included sourcing and cleaning the dataset, aggregating data by postal codes, and setting up accurate geographical mapping. It also involved formatting, implementing filters, and iterative refinement to ensure clarity and usability. These behind-the-scenes efforts made the final product polished and insightful.
    

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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
