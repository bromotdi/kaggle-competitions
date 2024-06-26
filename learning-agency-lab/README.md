# The Learning Agency Lab - PII Data Detection
#### Develop automated techniques to detect and remove PII from educational data.

## Link: ![https://www.kaggle.com/competitions/pii-detection-removal-from-educational-data/overview](https://www.kaggle.com/competitions/pii-detection-removal-from-educational-data/overview)

### Overview

![image](https://github.com/bromotdi/kaggle-competitions/assets/80320446/be49e574-cf9a-46f8-8f79-d2708b9bec32)

The goal of this competition is to develop a model that detects personally identifiable information (PII) in student writing. Your efforts to automate the detection and removal of PII from educational data will lower the cost of releasing educational datasets. This will support learning science research and the development of educational tools.
Reliable automated techniques could allow researchers and industry to tap into the potential that large public educational datasets offer to support the development of effective tools and interventions for supporting teachers and students.

### Description
In today’s era of abundant educational data from sources such as ed tech, online learning, and research, widespread PII is a key challenge. PII’s presence is a barrier to analyze and create open datasets that advance education because releasing the data publicly puts students at risk. To reduce these risks, it’s crucial to screen and cleanse educational data for PII before public release, which data science could streamline.

Manually reviewing the entire dataset for PII is currently the most reliable screening method, but this results in significant costs and restricts the scalability of educational datasets. While techniques for automatic PII detection that rely on named entity recognition (NER) exist, these work best for PII that share common formatting such as emails and phone numbers. PII detection systems struggle to correctly label names and distinguish between names that are sensitive (e.g., a student's name) and those that are not (e.g., a cited author).

Competition host Vanderbilt University is a private research university in Nashville, Tennessee. It offers 70 undergraduate majors and a full range of graduate and professional degrees across 10 schools and colleges, all on a beautiful campus with state-of-the-art laboratories. Vanderbilt is optimized to inspire and nurture cross-disciplinary research that fosters groundbreaking discoveries.

For this competition, Vanderbilt has partnered with The Learning Agency Lab, an Arizona-based independent nonprofit focused on developing the science of learning-based tools and programs for the social good.

Your work in creating reliable automated techniques to detect PII will lead to more high-quality public educational datasets. Researchers can then tap into the potential of this previously unavailable data to develop effective tools and interventions that benefit both teachers and students.

### Evaluation
Submissions are evaluated on micro 𝐹𝛽, which is a classification metric that assigns value to recall and precision. The value of 𝛽 is set to 5, which means that recall is weighted 5 times more heavily than precision.
