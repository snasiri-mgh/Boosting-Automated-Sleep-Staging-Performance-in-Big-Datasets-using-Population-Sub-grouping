# Boosting-Automated-Sleep-Staging-Performance-in-Big-Datasets-using-Population-Sub-grouping
For this issue we specifically focused on two elements highlighted by this call:
- Using big data to identify distinct subgroups of patients or trait clusters, and using this for
- Improving the accuracy of the diagnosis of sleep disorders.
In this work, we develop an approach for the sub-grouping of a large population in a robust feature space. 
We hypothesize that training an algorithm on such data without accounting for this diversity can cause underperformance. 
Moreover, test data from an unseen patient may have unexpected sensor misplacement, different instrumental noise. 
This work proposes a novel method to learn relevant individuals based on their similarities. 
The proposed method embeds all data into a shared and robust feature space. Individuals, that share strong statistical relationships and are 
more similar based on their EEG signals, are clustered in this feature space before being passed to a deep learning framework for classification. 
Sub-grouping of the population demonstrates that the clustering approach significantly boosts performance compared to state-of-the-art deep learning approaches. 
We show that taking account of the inherent inter-subject variability of EEG signals between different individuals and implementing methods 
to handle this issue and find a robust space for automating sleep staging, improves the generalization capability of machine learning methods 
EEG-based clinical applications.
