# Coding Challenge

Develop a service to find relevant news for a particular Category and Country. The json output from NEWS API should be further filtered for relevant keyword provided to the Micro-service (example Keyword = Tendulkar).

The service should be accessible via web browser on internet and end user should be able to view results by changing previously listed parameters. Output of this service should be JSON. And the service should be ready (in Git repository) to be released to production or live environment.

Write test cases and deploy the service on any one of GCP, AWS or Any other cloud provider for bonus marks.

In output, display following:
- Country
- Category
- Filter keyword
- News Title
- Description (first 100 words)
- Source News URL

In case of bad parameters the API should return proper error messages.


## API to fetch news data:

`https://newsapi.org/v2/top-headlines?country=us&category=business&apiKey={api-key}`

API Key: eadb6da4bb5847a8b5f5b8a633e53ab9

**Please also keep in mind that you shouldnʼt make the API call if you have
made the call using same parameters in last 10 minutes**
