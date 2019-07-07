<p align="center">
  <img src="https://signalone.app/assets/common/logo_signalone_color.png"/>
</p>

### SignalOne Web Push Notification Plugin




---

[SignalOne.app](https://signalone.app/) is a free push notification service for mobile apps. This plugin makes it easy to integrate your native Android or Amazon app with SignalOne.



How to Use
-------------

#WebPush


 Include the SignalOne to html---> head
```javascript

<script src="https://cdn.signalone.app/sdks/SignalOneSDK.js" async=""></script>
<script>
  var SignalOne = window.SignalOne || [];
  SignalOne.push(function() {
    SignalOne.init({
      appId: "********-****-****-****-************",
    });
  });
</script>


```

