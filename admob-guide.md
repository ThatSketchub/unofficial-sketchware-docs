---
description: A detailed guide on everything AdMob
---

# AdMob Guide

### Creating an AdMob Account

If you don't have an AdMob account, go to [AdMob](https://apps.admob.com/signup) to sign up.

You are set if you are navigated to the screen below

![AdMob page](.gitbook/assets/image%20%287%29%20%281%29%20%281%29%20%281%29.png)

## Creating an AdMob unit

An ad unit is one or more Google ads displayed using one piece of the AdSense ad code. You need to generate an Ad Unit to show ads inside your application.

### Create an Ad Unit inside your AdMob account

 Under your AdMob console, click on `Apps` and click on `Add App`. Follow the steps to add the app.

Enter an app name, select `Android`, and click `Add`

![Adding an app not on the Play Store](.gitbook/assets/image%20%2818%29.png)

On the next page, click `Next: Create Add Unit`

![](.gitbook/assets/image%20%2837%29.png)

{% hint style="info" %}
You don't need the App ID for Sketchware
{% endhint %}

On the next page, click either `Banner` or `Interstitial`

![](.gitbook/assets/image%20%2815%29%20%282%29%20%281%29.png)

{% hint style="success" %}
You can specify ad type \(Text, Image, and rich media or Video\), and more under `Advanced Settings`.
{% endhint %}

Enter an ad unit name, and click `Create Ad Unit`

![](.gitbook/assets/image%20%2823%29.png)

Ignore the steps on the next screen and copy the ad unit ID \(the one at the bottom\). You will need it for the next step.

![Ad unit sucessfully created](.gitbook/assets/image%20%2830%29.png)

### Add Ad Unit ID inside Sketchware

[Navigate to the Library Manager](https://sketchdocs.sketchub.in/library#library), and select AdMob.

#### Add Ad Units

Tap `Add Manually`

Enter the `Ad Unit Name` you used to create the ad unit in AdMob, and paste the `Ad Unit ID` you copied earlier, then click `Add`.

![Adding the Ad Unit](.gitbook/assets/image%20%2829%29%20%281%29%20%281%29%20%281%29.png)

Repeat until you have both Banner and Interstitial ad units then click `Next`.

#### Assign Ad Unit IDs

Click on `edit` next to Banner AD and select the Ad Unit you added in the last step that will be used for Banner Ads. 

![](.gitbook/assets/image%20%282%29.png)

Repeat until an ad unit is assigned for Interstitial. It should look similar to this:

![](.gitbook/assets/image%20%2828%29.png)



#### Configure Test Devices

Click on `Add Test Devices` and click `Add`. Click `Next`.

![](.gitbook/assets/image%20%2817%29%20%281%29%20%281%29%20%281%29.png)

#### Review Information

Check that all the information is correct, then click `Save`.

![](.gitbook/assets/image%20%2836%29.png)

Congratulations, you have successfully added ads to your app.

{% hint style="warning" %}
Ads will only show if the app is signed, and it may take over a week for real ads to show.

For more information, see [this blog post](https://blog.sketchub.in/2020/03/why-my-admob-ads-are-not-showing-in.html). 
{% endhint %}

