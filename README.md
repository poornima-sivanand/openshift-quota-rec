# Openshift Quota Research and Development

The following exercise is for assessing Province of BC's OpenShift quota, resource, limits and usage, and making various data models and recommendations for improving resource allocation and capacity planning.
  
## Problem Statements

1. We have to charge them based on requests in a year's time and we don't know if the quota sizes are accurate and saving them money 

2. Users don't understand the significance of quota, usage, requests and limits. 

3. Users are currently requesting too much CPU and not using it which could mean they are being charged higher than what is required.

4. Users are currently requesting very little CPU and using the limits to run their application which could mean they wouldn't be charged for what they use and will be burning out resources in the cluster which is a way of misusing our investment.

## Questions for Problem Statements

1. What are the correct T shirt sizes required to optimally use resources and save costs?
2. How can we configure our usage, requests, limit and quota in the most efficient manner?
3. If we properly configure the consumption, how many more projects can we provision in our namespace?
4. If we properly configure the consumption, how much money a business area save?
5. How much quota should we recommend a new project belonging to a specific category?

5. The patterns currently being used would be copied into public cloud and this would become an issue.
