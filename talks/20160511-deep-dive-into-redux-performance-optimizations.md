---
{
  "context": "http://schema.org",
  "type": "Educational event",
  "duration": "P30M",
  "github": "https://api.github.com/repos/BarcelonaJS/speakers/issues/11",
  "id": "20160511-deep-dive-into-redux-performance-optimizations",
  "performer": {
    "type": "Person",
    "githubId": 25742,
    "id": "ilya-zayats",
    "name": "Ilya Zayats",
    "location": "Barcelona, Spain",
    "github": "somebody32",
    "gravatar": "",
    "url": "https://api.github.com/users/somebody32",
    "image": "https://avatars.githubusercontent.com/u/25742?v=3",
    "twitter": "somebody32"
  },
  "superEvent": {
    "type": "Social event",
    "url": "/event/20160511-barcelonajs-may-2016.html",
    "id": "20160511-barcelonajs-may-2016",
    "name": "BarcelonaJS May 2016"
  },
  "name": "Deep Dive into Redux Performance Optimizations",
  "startDate": "2016-05-11T18:45:00Z",
  "url": "/talk/20160511-deep-dive-into-redux-performance-optimizations.html",
  "inLanguage": "en",
  "level": "advanced | expert",
  "tags": [
    "react",
    "redux",
    "performance"
  ]
}
---


Redux + React allow you to write applications and rarely think about performance: everything is fast out of the box. But what to do if you need to scale your app to handle and display 10x more data? Then you can see perf problems even with React.

In this talk, I will show what react-redux does under the hood to make your app fast and what techniques you should avoid to keep it in that state even with 10x data grow.