# HMS - Harmful Brain Activity Classification

### Link:

![https://www.kaggle.com/competitions/hms-harmful-brain-activity-classification](https://www.kaggle.com/competitions/hms-harmful-brain-activity-classification)

### Overview
The goal of this competition is to detect and classify seizures and other types of harmful brain activity. You will develop a model trained on electroencephalography (EEG) signals recorded from critically ill hospital patients.
Your work may help rapidly improve electroencephalography pattern classification accuracy, unlocking transformative benefits for neurocritical care, epilepsy, and drug development. Advancement in this area may allow doctors and brain researchers to detect seizures or other brain damage to provide faster and more accurate treatments.

### Description
From stethoscopes to tongue depressors, doctors rely on many tools to treat their patients. Physicians use electroencephalography with critically ill patients to detect seizures and other types of brain activity that can cause brain damage. You can learn about how doctors interpret these EEG signals in these videos:

Currently, EEG monitoring relies solely on manual analysis by specialized neurologists. While invaluable, this labor-intensive process is a major bottleneck. Not only can it be time-consuming, but manual review of EEG recordings is also expensive, prone to fatigue-related errors, and suffers from reliability issues between different reviewers, even when those reviewers are experts.

Competition host Sunstella Foundation was created in 2021 during the COVID pandemic to help minority graduate students in technology overcome challenges and celebrate their achievements. These students are vital to America's technology leadership and diversity. Through workshops, forums, and competitions, the Sunstella Foundation provides mentorship and career advice to support their success.

Sunstella Foundation is joined by Persyst, Jazz Pharmaceuticals, and the Clinical Data Animation Center (CDAC), whose research aims to help people preserve and enhance brain health.

Your work in automating EEG analysis will help doctors and brain researchers detect seizures and other types of brain activity that can cause brain damage, so that they can give treatments more quickly and accurately. The algorithms developed in this contest may also help researchers who are working to develop drugs to treat and prevent seizures.

Examples of EEG Patterns with Different Levels of Expert Agreement:

![image](https://github.com/bromotdi/kaggle-competitions/assets/80320446/01002efa-a974-43c9-9905-a130acfcf5d8)

There are six patterns of interest for this competition: seizure (SZ), generalized periodic discharges (GPD), lateralized periodic discharges (LPD), lateralized rhythmic delta activity (LRDA), generalized rhythmic delta activity (GRDA), or “other”. Detailed explanations of these patterns are available here.

The EEG segments used in this competition have been annotated, or classified, by a group of experts. In some cases experts completely agree about the correct label. On other cases the experts disagree. We call segments where there are high levels of agreement “idealized” patterns. Cases where ~1/2 of experts give a label as “other” and ~1/2 give one of the remaining five labels, we call “proto patterns”. Cases where experts are approximately split between 2 of the 5 named patterns, we call “edge cases”.

### Evaluation
Submissions are evaluated on the Kullback Liebler divergence between the predicted probability and the observed target.
