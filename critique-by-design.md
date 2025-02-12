| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Title
Text here...

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: the visualization
Black Wealth Data Center. (2023). Number of Employer Firms, by Firm Receipt Amount, by Race/Ethnicity (Nationwide and Statewide, 2023). Retrieved from https://blackwealthdata.org/explore/business

![image](https://github.com/user-attachments/assets/0f4f4730-1f70-47b5-bd56-04fea4e7c859)

I selected this data visualization because I am very interested in economic disparities in relation to access to financial opportunities among different racial groups. Based on the title alone, I expected these disparities to be demonstrated through the visualization. I was also interested in examining state-level differences compared to national trends, as I was curious about how these proportions might change regionally. Additionally, I wanted to identify which states might have the largest disparities to begin considering other variables that could contribute to these differences.

## Step two: the critique
Overall, I believe the data visualization had good intentions in highlighting disparities among racial and ethnic groups regarding access to business loans. However, the presentation contained an overwhelming amount of information, with multiple navigation points (e.g., state differences, firm size differences), which made the main message somewhat convoluted.

While the segmentation was unique, there should be a clearer hierarchy to guide the audience’s focus. The visualization’s biggest weakness, in my opinion, is the lack of clarity due to each racial group having a different x-axis scale. This makes it difficult to accurately determine which group received the most or least funding.

To improve clarity, the primary visualization should feature a single bar graph comparing different racial groups within the same year. Additionally, including a proportional rate percentage—reflecting total loan dollars received relative to the number of employees in each group’s firms—would help account for differences in loans received given firm size, as well as population disparities. Since white Americans constitute the majority population, this adjustment would mitigate disproportionate effects and provide a more accurate comparison.

Additionally, state-specific data can be included as supplementary information, perhaps in an appendix or as an optional interactive feature, but the main visualization should focus on delivering a clear, concise message.

## Step three: Sketch a solution
Below are a few simple rough sketches I formulated:

![image](https://github.com/user-attachments/assets/d3e1c039-b4a5-4a5b-b904-0721113dc01e)

![image](https://github.com/user-attachments/assets/1fb81a7a-fa2e-4e39-9be3-684e4e5edce1)

![image](https://github.com/user-attachments/assets/f64110ce-f76c-4660-b9e3-886ab93ebd30)

![image](https://github.com/user-attachments/assets/7731eaaf-44d5-4dd3-b9b5-07c012cdde23)





## Step four: Test the solution

Interview Questions:

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Is there anything you would change or do differently?

Results: 

| Question | Interview 1 | Interview 2 |
|----------|-------------|-------------|
| Is there anything you would change or do differently?         |   Create more clear labels for axes     |    Condense information by only including proportions and not raw dollar amounts.       |
|   Is there anything you find surprising or confusing? |      Unclear on representation in changes in race/ethnicity--need legend       |    Surprised how you were able to convey sensible information through a visual graph. Also liked how new layers were added on through each visualization sketch.    |
| Can you describe to me what this is telling you?       |  It is showing the disparities in business opporutnities in America           |  I'm seeing the differences in treatment of different racial groups            |

**Interviews conducted with students from the Master of Arts Management Program and Master of Entertainment Industry Management

Synthesis: 
-Will incorporate more labels and a legend for the graph
-May try to consolidate information and remove intersecting line graph to avoid confusion/overwhelming amount of data.
-More clear identification of y-label/variable that will be at focus. 
_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

## Step five: build the solution

I decided to utilize Python via Google Co-Lab to create my data visualization. I first uploaded the dataset to a Generative AI platform to help me generate code. 

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

