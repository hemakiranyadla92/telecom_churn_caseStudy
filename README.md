# Telecom Churn Case Study

We consider the customer lifecycle to consist of three stages:

The "good" phase: During this time, the client is satisfied with the assistance and acts normally.

The "action" phase is when the customer's experience starts to go south. For example, he or she receives an alluring offer from a rival, is subjected to unfair charges, is dissatisfied with the calibre of the service, etc. 
The customer typically behaves differently during this phase than during the "good" months. 
Additionally, it is critical to identify high-churn-risk customers during this phase because it allows for the implementation of corrective measures (e.g., matching the competitor's offer, improving service quality, etc.).

The "churn" phase: During this time, the client is considered to have left. This stage is how we define churn. Not to mention, you are not able to predict with this data at the time of prediction (i.e., the action months). 
Consequently, we discard all data associated with this phase after classifying churn as 1/0 based on this phase information.

In this instance, the first two months are the "good" phase, the third month is the "action" phase, and the fourth month is the "churn" phase because we are working over a four-month period.
