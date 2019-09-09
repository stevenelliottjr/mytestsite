<dl>
<script src="https://static.landbot.io/landbot-widget/landbot-widget-1.0.0.js"></script>
<script>
  var myLandbot = new LandbotLivechat({
    index: 'https://landbot.io/u/H-253645-BNNP8RPCGCTIZ6SF/index.html',
  });
</script><script>
  // Show a proactive message on landbot load
  myLandbot.on('landbot-load', function() {
    myLandbot.sendProactive({
  "message": "Welcome to UCard, Click the chat icon to begin!",
  "author": "UCard",
  "avatar": "https://storage.googleapis.com/media.helloumi.com/channels/71J4U9SD95WQZ98UR8T6X7BA7RG35PXC.png",
  "extra": {
    "hide_textbox": true
  }
});
  });
</script>
  </dl>
