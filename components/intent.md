---
description: A component that is used to navigate between activities.
---

# Intent

## Examples

### Basic Examples

#### Start a Activity

![A basic activity starting.](../.gitbook/assets/img_20200518_171828.jpg)

{% hint style="info" %}
This is not closing the activity that was started previously.
{% endhint %}

#### Start a Activity and close the previous one

![Starts a Activity then closes the previous one](../.gitbook/assets/img_20200518_173912.jpg)

{% hint style="info" %}
This will close the Activity that was started previously.
{% endhint %}

## Blocks

### setData

Used to point to the location of a data object \(like a file for example\), while putExtra adds simple data types \(such as an SMS text string for example\).

![setData](https://docs.sketchware.io/docs/assets/intent/set-data.png)

### setScreen

Sets the screen to navigate to.

![setScreen](https://docs.sketchware.io/docs/assets/intent/set-screen.png)

### **putExtra**

 Pass data to another Activity. After you pass the data, you retrieve the data using the `Activity getExtra key []` block.

![putExtra](https://docs.sketchware.io/docs/assets/intent/put-extra.png)

### setFlags

Change the behavior of an activity.

1. `SINGLE_TOP` — Organizes the views in a way that if the view you’re about to transition to was already called before, it would bring that view to the top rather than putting another copy on the top.
2. `CLEAR_TOP` - Clears all the previous views.

![setFlags](https://docs.sketchware.io/docs/assets/intent/set-flags.png)

### startActivity

Start a new activity. 

![startActivity](https://docs.sketchware.io/docs/assets/intent/start-activity.png)



