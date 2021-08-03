# How to create notification

Should be executed in [background script](https://developer.chrome.com/docs/extensions/mv3/background_pages/),
which is [specified in manifest.json](/chrome-extension/background_script).
Also [notifications persmissions](/chrome-extension/notifications) should be set.

```javascript
chrome.notifications.create( 'myid', { title: 'Title', message: 'Content' } );
```

- create - creates notification
- myid - id of a notification to create
- title: - notification popup title
- message: - message body to show in nofitication popup

group: notification