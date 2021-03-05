---
description: Get to the properties by clicking on a widget or layout.
---

# Properties

{% hint style="info" %}
On this page widgets and layouts will be refired collectively as widgets.
{% endhint %}

Open the properties of a widget by clicking on that widget:

![](../.gitbook/assets/open_properties_bottom.gif)



You can also see a complete list of properties by clicking the widget and clicking _see all_. There are certain properties that can only be changed in the _see all_  list, for example the `enabled` property, or the `single line` property of an edittext.

![Accessing the see all list](../.gitbook/assets/open_properties_all.gif)

## List of properties

#### ![](../.gitbook/assets/rename_96_blue.png) Widget ID

This is unique ID of widget or layout you used. While programming the app, it is needed.

{% hint style="success" %}
For large apps, make your widget's ID rememberable, since this is how you will be able to find widgets when programming your app. For example, for title, "txt\_title", "btn\_submit" etc.
{% endhint %}

### Layout Properties

#### ![](../.gitbook/assets/height_96.png) Width and height

You can set your widget's dimensions. There are few types available.

| Type | Explanation |
| :--- | :--- |
| match\_parent | The width/height will be matched to the layout it is inside of, in simple words, it will be maximum height/width. |
| wrap\_content | The width/height will be set automatically according to contents in it. It will only take up what the widget needs. |
| Custom \(in dp\) | Set custom height/width according to requirement. For example, for small icon, you can use 40x40 \(width x height\). Keep in mind that if you used a fixed dp, the widget may be cut off in devices with smaller sized screens. |

#### ![](../.gitbook/assets/collect_48.png) Padding

Padding is used to add space **inwards** of the widget

{% tabs %}
{% tab title="Input" %}
Padding is added to "Linear Layout"

![Padding \(Pic. 4\)](../.gitbook/assets/padding_menu.jpg)
{% endtab %}

{% tab title="Output" %}
A padding of 8 dp is applied on _Linear Layout_

![Output \(Pic. 5\)](../.gitbook/assets/padding_output.jpg)
{% endtab %}
{% endtabs %}

#### ![](../.gitbook/assets/insert_white_space_48.png) Margin

Margin is used to add space **outwards** of the widget. It is same as [padding](properties.md#padding) but outside of the widget.

#### ![](../.gitbook/assets/gravity_96.png) Gravity and Layout Gravity

In simple word, gravity is used to set alignment of **contents in the widget** whereas layout gravity is used to set alignment of **the widget.**

![Gravity Example \(Pic. 6\)](../.gitbook/assets/gravity.jpg)

#### \*\*\*\*![](../.gitbook/assets/one_to_many_48.png) **Weight**

Weight is very important property, even if it is used rarely. It helps to keep widget stable. It is better that setting a fixed dp, because it will change the widget's size to fit the device it is on. For more information, see [this article](https://medium.com/sketchware/tip-understanding-and-using-weight-property-2d542d2de0bf).  
**Examples:**

{% tabs %}
{% tab title="Example 1" %}
It can be used to set width of two or more widgets equal by setting both widgets gravity to 1 \(or any equal value\).

![Example 1 \(Pic. 7\)](../.gitbook/assets/weight1.jpg)
{% endtab %}

{% tab title="Example 2" %}
It can be used to fit the widget to screen like this:

![Example 2 \(Pic. 8\)](../.gitbook/assets/weigh2.jpg)
{% endtab %}
{% endtabs %}

#### ![](../.gitbook/assets/one_to_many_48.png) Weight Sum

This is one of most unused thing in Sketchware. Nobody has even seen someone using it yet, so there is no information available. You can refer to Stackoverflow if you needed it. [https://stackoverflow.com/a/7452788/9300428](https://stackoverflow.com/a/7452788/9300428)

![](../.gitbook/assets/no_need_2_thanks.jpg)

### Text Properties

Text properties are available only for text containing widgets i.e.:

* TextView ![](../.gitbook/assets/widget_text_view.png)
* EditText  ![](../.gitbook/assets/widget_edit_text.png) 
* Button  ![](../.gitbook/assets/widget_button.png) 
* CheckBox  ![](../.gitbook/assets/widget_check_box.png) 
* Switch  ![](../.gitbook/assets/widget_switch.png) 

| Title | Explanation |
| :--- | :--- |
| ![](../.gitbook/assets/abc_96.png) text | Used to set text of the widget |
| ![](../.gitbook/assets/event_on_text_changed_48dp.png) text size | Used to set text size of the widget |
| ![](../.gitbook/assets/abc_96_color.png) text style | Used to format text in **bold**, _italic_ or _**both**_ |
| ![](../.gitbook/assets/color_palette_48.png) text color | Used to set color of text |
| ![](../.gitbook/assets/help_96_blue.png) hint | It is text shown when edittext is empty |
|  ![](../.gitbook/assets/color_palette_48.png) hint color | Used to set color of hint of edittext |
| ![](../.gitbook/assets/horizontal_line_48.png) single line | Restrict the widget to use only single line |
| ![](../.gitbook/assets/numbers_48.png) lines | Restrict the widget to use only specified number of lines |
| ![](../.gitbook/assets/keyboard_48.png) input type | Used to accept only specific type of text |
| ![](../.gitbook/assets/keyboard_48.png) ime option | Used to set keyboard's main button |

### Image Properties

#### ![](../.gitbook/assets/ic_picture_48dp.png) Image \(Only in ImageView\)

It set image to the imageview. The Image should be available in [Image Manager](https://wiki.sketchub.in/configuration/image).

#### ![](../.gitbook/assets/enlarge_48.png) Scale type \(Only in ImageView\)

| Type | Explanation \(Source: abhiandroid.com\) |
| :--- | :--- |
| FIT\_XY | Fill the image from x and y coordinates of the container |
| FIT\_START | Scale the image from start of the container |
| FIT\_CENTER | Scale the image from center |
| FIT\_END | Scale the image from the end of the container |
| CENTER | Center the image but doesn’t scale the image |
| CENTER\_CROP | Scale the image uniformly |
| CENTER\_INSIDE | Center the image inside the container, rather than making the edge match exactly |

![Examples \(Pic. 9\)](../.gitbook/assets/scaletype.jpg)

#### ![](../.gitbook/assets/variation_48.png) Background Resource

Background resource is used for setting custom background of the widget or layout. **You will need to** [**add image in Image Manager**](https://wiki.sketchub.in/configuration/image) **to set background image.**

#### \*\*\*\*![](../.gitbook/assets/color_palette_48.png) **Background Color**

Used to set background color of the widget.

#### ![](../.gitbook/assets/light_on_48.png) Enabled

| Values | Explanation |
| :--- | :--- |
| ON | Enables the widget, allowing codes and users to manipulate it. |
| OFF | Disables the widget, hence nobody will have access, even your codes \(until you don't enable it back\). |

#### ![](../.gitbook/assets/event_animation_repeat_48dp.png) Rotate

It rotates the widget with specific angle you give.

#### ![](../.gitbook/assets/swipe_right_48.png) Translation X and Y

This is rarely used but important property, it moves the widget from its original position. For example, in this image \(Pic.8\), both widgets have -45 Y translation, which moves them horizontally.

![Example \(Pic.8\)](../.gitbook/assets/translationxy.jpg)

#### ![](../.gitbook/assets/resize_48.png) scaleX and scaleY

Scale is used to resize widgets; it also resizes the contents in it \(in linear layouts and scroll view\). It is not used usually in Sketchware because it stretches everything and make the UI worse if not used properly.

