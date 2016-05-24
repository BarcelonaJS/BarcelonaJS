---
{
  "context": "http://schema.org",
  "type": "Educational event",
  "duration": "P30M",
  "github": "https://api.github.com/repos/BarcelonaJS/speakers/issues/16",
  "id": "20160622-build-and-manage-a-serverless-api-in-js",
  "performer": {
    "type": "Person",
    "githubId": 172072,
    "id": "nicolas-grenie",
    "name": "Nicolas Grenié",
    "location": "San Francisco",
    "github": "picsoung",
    "gravatar": "",
    "url": "https://api.github.com/users/picsoung",
    "image": "https://avatars.githubusercontent.com/u/172072?v=3",
    "twitter": "picsoung"
  },
  "superEvent": {
    "type": "Social event",
    "url": "/event/20160622-barcelonajs-june-2016.html",
    "id": "20160622-barcelonajs-june-2016",
    "name": "BarcelonaJS June 2016"
  },
  "name": "Build and manage a Serverless API in JS",
  "startDate": "2016-06-22T18:45:00Z",
  "url": "/talk/20160622-build-and-manage-a-serverless-api-in-js.html",
  "level": "beginner",
  "language": "en",
  "tags": ["serverless", "APIs", "AWS Lambda"]
}
---

There is currently a major shift sweeping over the software industry. We went from monolithic apps, to API-driven apps, and now software engineers are breaking their apps into "micro-services".
Managing and connecting those different micro-services could be a hassle for DevOps.
AWS offers an interesting service with Lambda that let you create microservices easily for a very cheap price. With the recent announcement of the API gateway, it lets you create a 100% serverless microservice-based infrastructure for your API and app.

To simplify the creation and the maintenance of a such infrastructure, the community have came up with a framework: Serverless (previously: JAWS)
In this talk we will cover serverless principles using AWS Lambda and Serverless framework to build APIs.
