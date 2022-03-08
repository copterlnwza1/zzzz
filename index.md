Skip to content
Search or jump to…
Pull requests
Issues
Marketplace
Explore
 
@copterlnwza1 
 The password you provided is in a list of passwords commonly used on other websites. To increase your security, you must update your password. After April 7, 2022 we will automatically reset your password. Change your password on the settings page.

Read our documentation on safer password practices.

copterlnwza1
/
NEW
Public
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Settings
NEW/index.html
@copterlnwza1
copterlnwza1 Update index.html
Latest commit 43b47a3 22 minutes ago
 History
 1 contributor
92 lines (92 sloc)  2.07 KB
   
<!DOCTYPE html> 
<html> 
<head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=0,viewport-fit=cover">
<title>LIFF - LINE Front-end Framework</title> 
</head> 
<body>
  <script src="https://static.line-scdn.net/liff/edge/versions/2.16.0/sdk.js"></script>
  <script> 
    async function main() {
      await liff.init({ liffid: "1656955999-BQ48GxYa" }) 
      await liff.shareTargetPicker([
    {
    type: "flex",
    altText: "Flex Message from Share Target Picker", 
    contents: {
  "type": "bubble",
  "size": "giga",
  "hero": {
    "type": "image",
    "url": "https://sv1.picz.in.th/images/2022/03/08/rCClfZ.jpg",
    "size": "full",
    "aspectRatio": "1:1",
    "action": {
      "type": "uri",
      "uri": "https://lin.ee/APJg1NR"
    },
    "margin": "none"
  },
  "footer": {
    "type": "box",
    "layout": "vertical",
    "spacing": "lg",
    "contents": [
      {
        "type": "button",
        "style": "primary",
        "height": "md",
        "action": {
          "type": "uri",
          "label": "รับเครดิตฟรี",
          "uri": "https://lin.ee/APJg1NR"
        },
        "margin": "md",
        "gravity": "center",
        "color": "#FAC101"
      },
      {
        "type": "button",
        "action": {
          "type": "uri",
          "label": "ส่งให้เพื่อน",
          "uri": "https://liff.line.me/1656955999-BQ48GxYa"
        },
        "color": "#FAC101",
        "style": "primary",
        "gravity": "center",
        "margin": "md",
        "height": "md"
      },
      {
        "type": "spacer",
        "size": "md"
      }
    ],
    "flex": 0,
    "margin": "none",
    "backgroundColor": "#A71F0C",
    "borderWidth": "none",
    "borderColor": "#FAC101",
    "background": {
      "type": "linearGradient",
      "startColor": "#C61B11",
      "endColor": "#C61B11",
      "angle": "0deg"
    }
  },
  "styles": {
    "footer": {
      "separator": true
    }
  }
}
    }
   ])
   liff.closeWindow()
  }
  main() 
 </script>
</body> 
</html>
© 2022 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
Loading complete
