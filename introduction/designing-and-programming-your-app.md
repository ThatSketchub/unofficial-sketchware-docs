# Designing and Programming your app

In the last tutorial you created your first app. If you try to run it by clicking the blue Run button, you will install an empty app on your device since you haven't designed or programmed your app yet.

## Basic Concept

There are two parts to creating your app:

1. Designing
2. Programming

Designing is only about how the app looks, the UI. Programming is about making the UI interact with the user. For example, making something happen when a button is clicked.

### View Editor <a id="e471"></a>

This is View Editor, where you **design** your application. On the left, you will find **Layouts** and **Widgets**.

1. **Layouts** — **container** that can hold **widgets** in different orientations
2. **Widgets** — basic user interface components, such as **Text** or **Button**

To place these, you have to long-click and drag them to the editor, like this:

**Insert here**

But as you start placing things inside the editor, you will feel like you can only place things vertically below each widget. You might ask, “How do I place them next to each other?” This is where a **LinearLayout** comes in!

By using different **layouts**, you will be able to place things in different orientations! \(H\) stands for Horizontal, and \(V\) stands for Vertical.

Now that you have added some widgets, you may have realized that you can't scroll. You will need to add a ScrollView to be able to scroll. ScrollViews come in both \(H\) for Horizontal, and \(V\) for Vertical. You can only place one widget in the ScrollView, so it is best to put a LinearLayout inside.



