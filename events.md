---
description: >-
  Events are Triggers which occurs when user open, close, press button, long
  click button, download completion etc.
---

# Events

## ![](.gitbook/assets/ic_cycle_color_48dp.png) Activity

Source: [https://medium.com/sketchware/activity-lifecycle-in-android-applications-1b48a7bb584c](https://medium.com/sketchware/activity-lifecycle-in-android-applications-1b48a7bb584c)

![Activity Life-cycle \(Pic. 9\)](.gitbook/assets/activity_life_cycle.png)

### ![](.gitbook/assets/widget_source.png) onCreate

This is the event, when app is started. This is a good place to initialize any data such as variables or lists. In Sketchware, this event is provided by default.

### ![](.gitbook/assets/widget_source.png) onBackPressed

As the name suggests, the blocks in this event will run when back button is pressed from your phone.

### ![](.gitbook/assets/widget_source.png) onStart

This event occurs when you open/reopen the activity. See the Pic.9 for more details.

### ![](.gitbook/assets/widget_source.png) onPostCreate

This event is called when activity start-up or onStart is complete.

### ![](.gitbook/assets/widget_source.png) onResume

This event is called whenever the user returns to the activity after leaving the activity — such as receiving a call, pressing the home button, turning off the screen, or transitioning to another activity.

### ![](.gitbook/assets/widget_source.png) onPause

This event occurs when the user is leaving your activity.

### ![](.gitbook/assets/widget_source.png) onStop

When your activity is no longer visible to the user. This is usually a good point to pause any ongoing process, such as MediaPlayer or SoundPool.

### ![](.gitbook/assets/widget_source.png) onDestroy

When the activity is closed, this will last event of Activity. It also occurs when somebody close the app correctly. \(Force close can be exception\)

## ![](.gitbook/assets/multiple_devices_48.png) View

### ![](.gitbook/assets/event_on_click_48dp.png) onClick

A simple Event when that specific widget is clicked.

### ![](.gitbook/assets/event_on_text_changed_48dp.png) onTextChanged

Whenever the text in 'edittext' is changed.

{% hint style="success" %}
**onTextChanged** also occurs when you set text by using blocks
{% endhint %}

### ![](.gitbook/assets/event_on_check_changed_48dp.png) onCheckChanged

This event occurs when the value of Checkbox/Switch is changed.

{% hint style="success" %}
**onCheckChanged** also occurs when you change check by using blocks
{% endhint %}

![An Example \(Pic. 10\)](.gitbook/assets/check_uncheck.jpg)

### ![](.gitbook/assets/event_on_progress_changed_48dp.png) onProgressChanged 

This event occurs when progress is changed for seekbar. \(Only for Seekbar\)

### ![](.gitbook/assets/event_on_start_tracking_touch_48dp.png) onStartTrackingTouch

This event occurs when the user holds the seekbar to change it. \(Only for Seekbar\)

### ![](.gitbook/assets/event_on_stop_tracking_touch_48dp.png) onStopTrackingTouch

This event occurs when the user stop holding the seekbar when he is done. \(Only for Seekbar\)

MAPVIEW will be added soon.

### ![](.gitbook/assets/event_on_date_changed_48dp.png) onDateChange

This event occurs when the user selects a date in a CalendarView. \(Only for CalendarView\)

