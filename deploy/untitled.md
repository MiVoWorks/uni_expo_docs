# Deploy on Google Play and App Store

## Expo.io

Since this is an expo app, the complete up to date documentation for publishing your project can be found here.

{% embed url="https://docs.expo.io/versions/v36.0.0/distribution/building-standalone-apps/" %}

But in general, to simplify things

### To publish Android App.

You will need Google Play developer account. 25$/once. [Register here](https://play.google.com/apps/publish/signup).

In your project run

```
$ expo build:android --type app-bundle
```

{% hint style="warning" %}
 Follow the guidelines from expo, choose expo to handle the process. At the end you will get link where you can download your .**aab** file. This file will be around **50MB.** But when uploaded on google play will be around **15MB**. 
{% endhint %}

### To publish in Apple App Store

You will need Mac computer and Apple Developer account 99$/year. [Register here](https://developer.apple.com/programs/enroll/).

In you project run

```text
expo bi
```

Follow the onscreen instructions. Login with your developer account. After and .ipa file is made run the following command

```text
expo ui
```

{% hint style="warning" %}
This command will upload the .ipa in your itunes Connect. First you will need to create an app there. The build will be available in TestFlight. And you can move it to be ready for review, and submit for review on Apple Review Team.
{% endhint %}

