# [MIT HST.953x Collaborative Data Science for Healthcare](https://learning.edx.org/course/course-v1:MITx+HST.953x+1T2021)

## Course Syllabus

## Section 1: Setting the Stage

### What is Data Science
*Learning objectives*

In this section you will learn about: 

- The key ingredients for successful collaboration in data science
- The evaluation of machine learning systems using an example from radio astronomy

[Raw Transcript](raw_transcripts/01-1-definition_data_science.txt)
Presented by:
Kiri Wagstaff
National Aeronautics and Space Administration (NASA)


#### Definition of Data Science

Data science is an inter-disciplinary field that uses scientific techniques from statistics and computer science to systematically extract knowledge from data.

Suggested Readings:

[Donoho D. 50 years of data science. Journal of Computational and Graphical Statistics. 2017 Oct 2;26(4):745-66.](https://www.tandfonline.com/doi/full/10.1080/10618600.2017.1384734) 
[Blei DM, Smyth P. Science and data science. Proceedings of the National Academy of Sciences. 2017 Aug 15;114(33):8689-92.](https://www.pnas.org/content/114/33/8689.long) 

In this section, we cover some of the important steps for successful data analysis:

1. Developing a shared language
2. Adequate representation and justification of data
3. Getting to know your data
4. Dealing with missing data
5. Valid ranges of features
6. Evaluating analyses

#### Developing a shared language 

[Raw Transcript](raw_transcripts/01-2-developing_shared_language.txt)

Key Points:

- Same words can have different meanings, depending on the context
- Define terms/jargon when working in multidisciplinary teams to avoid confusion and errors

| Feature                     | Feature (Machine Learning) |
|-----------------------------|----------------------------|
| Feature (Planetary Science) | Height                     |
| Olympus Mons, Mars          | Area                       |
|                             | Albedo, etc.               |

#### Dealing with Missing Data

[Raw transcript](raw_transcripts/01-3-missing_data.txt)
Key points:

- Inspect your data to determine if there is missing data. Sometimes, missing data is coded as "99999"
- Why is the data missing? This requires you to know how the data was collected
- Sometimes, missing data arises because a value is unmeasurable (e.g. eccentricity cannot be calculated for a point such as a star)
- Don't just blindly fill ("impute") the missing values without first understanding why the value is missing