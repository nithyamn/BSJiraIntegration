# BSJiraIntegration


Jira Integration with BrowserStack.

![BrowserStack Logo](https://d98b8t1nnulk5.cloudfront.net/production/images/layout/logo-header.png?1469004780)


## Set the following environment variables before test execution
* BrowserStack Username and Accesskey

``
export BROWSERSTACK_USERNAME=<username>
``

``
export BROWSERSTACK_ACCESS_KEY=<accesskey>
``

* BrowserStack App hashed ID

``
export BROWSERSTACK_APP_ID=<app_hashed_id>
``


* Jira instance URL 

- If public:
``
export JIRA_URL=<something.atlassian.net>
``

- If self hosted
``
export JIRA_URL=<localhost:8090>
``

* Jira linked Email ID

``
export JIRA_EMAIL=<email_id>
``

* Jira API Token

``
export JIRA_API_TOKEN=<api_token>
``

## References
1. Code ref:  https://community.atlassian.com/t5/Answers-Developer-Questions/Create-issue-via-REST-API-useing-Java/qaq-p/518478
2. REST APIs: https://developer.atlassian.com/server/jira/platform/jira-rest-api-example-create-issue-7897248/
3. API Tokens: https://confluence.atlassian.com/cloud/api-tokens-938839638.html