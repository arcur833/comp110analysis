---
# Do not edit the text between these lines!
layout: default
---

# COMP 110 Data Analysis: Should Lectures Be Livestreamed?

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="<custom-path>/static/imgs/logo.png" alt="Image of Comp110 rainbow logo. "  width="500"/>

## Summary
In this analysis, I explored whether COMP 110 should provide livestreaming 
or recordings of in-person lectures. Using anonymized survey data from 764 
students, I analyzed the add_livestream column which asked students to rate 
their desire for livestreaming on a scale of 1-7.

## Analysis
The data strongly supports adding livestreaming to COMP 110. 301 out of 764 
students gave the highest possible rating of 7, and the majority of students 
rated it 5 or above regardless of their UNC status or prior programming experience.
I looked at the data in the add_livestream survey column, which asked 764 students to indicate their interest level regarding livestreaming on a scale from 1 (Strongly Disagree) to 7 (Strongly Agree). In my code, I first loaded both survey datasets through the use of the read_csv_rows and concat functions, and then selected and viewed the relevant data using the select and head functions. Using the count method, I saw that there were 301 out of 764 people who rated this item a 7 (Strongly Agree), with most of them giving it a rating of 5 or higher. I decided to generate three visualizations that would help me understand this phenomenon further. Through a bar chart, I could see how unanimous the respondents were on this issue. Through a boxplot, I found that this strong desire for livestreaming is universal across all UNC levels – freshman, sophomore, junior, senior, and graduate. With the violin plot, I was able to determine that no matter whether students had any previous experience in coding, they all desired to have lectures livestreamed. 

## Charts

![Chart 1](/comp110analysis/static/imgs/Chart1.png)

![Chart 2](/comp110analysis/static/imgs/Chart2.png)

![Chart 3](/comp110analysis/static/imgs/Chart3.png)

## Conclusion
These findings strongly point towards the benefits that can be brought 
about by including livestreaming or recorded lectures in COMP 110 classes. 
All the visualizations show that almost everyone indicated their demand for 
livestreaming at the highest level of 6 out of 7. In particular, in the 
bar graph, 301 out of 764 participants indicated their strong interest in 
the possibility by giving it the highest possible score of 7. The boxplot 
revealed that this preference is the same across the board for all UNC 
status groups (Freshman, Sophomore, Junior, Senior, and Graduate). Lastly, 
the violin plot demonstrated that no matter how much previous programming 
experience one might have, their demand is always high.

On the other hand, some costs associated with including such lectures 
should be considered. First of all, having a recording of lectures allows 
students to avoid visiting class, thus lowering attendance and damgaing 
the feeling of community within the class. Secondly, an investment in the 
technology required for livestreaming is needed for both professors and 
the university. Lastly, students watching recorded lectures risk falling 
behind due to lack of motivation.

Future research should examine the relationship between the add_livestream 
and ls_effective variables to determine if those who find lesson videos 
effective are the same individuals requesting livestreams. In addition, this 
research could be improved by conducting surveys that ask students if they 
would prefer recordings of full lectures or only the audio portions(and they 
follow on the slides, maybe then they are more enaged). Another possibility for 
further research is to survey students on whether optional attendance would influence
their engagement with the course content.

