Problem Statement:
X Education sells online courses to industry professionals. X Education needs help selecting the most
promising leads, i.e., the leads most likely to convert into paying customers. The company needs a model
wherein a lead score is assigned to each lead such that the customers with higher lead scores have a
higher conversion chance and the customers with lower lead scores have a lower conversion chance. The
CEO has given a ballpark of the target lead conversion rate to be around 80%.
Our Goals of the Case Study:
To build a logistic regression model to assign a lead score between 0 and 100 to each of the leads
which can be used by the company to target potential leads.
To adjust if the company's requirement changes in the future, you will need to handle these as well.
Summary:
• As we have checked Sensitivity, Specificity, Precision, and Recall as Metrics, we have
considered the optimal cutoff limit as 0.37 for calculating the final prediction.
• Accuracy, Sensitivity, and Specificity values of the test set are around 81%, 79%, and 82%
which are approximately closer to the respective values calculated using the trained set.
• Also, the lead score calculated in the trained set of data shows the conversion rate on the
final predicted model is around 80%.
• Hence overall this model seems to be good.
• Firstly, need to sort out the best prospects from the leads you have generated. 'TotalVisits',
'Total Time Spent on Website', and 'Page Views Per Visit' contribute most towards the
probability of a lead getting converted.
• Focus on converted leads.
• Hold question-answer sessions with leads to extract the right information you need about
them.
• Make further inquiries and appointments with the leads to determine their intention and
mentality to join online courses.
• API and Landing Page Submission have around 35-40% conversion rate but the count of
lead originating from them are considerable.
• Lead Add Form has a more than 90% conversion rate, but the count of lead is not very high.
• Lead Import and Quick Add From are very less in the count.
• Direct Traffic and Google are generating a h
