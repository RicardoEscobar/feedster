# Feedster
## Description
Practice more animation methods using a click event, `.toggle()` notification bell menu, and `.toggleClass` +1 button.

## Objective
Feedster wants to add a notification menu and a +1 button to their news feed. [Here's what it looks like]("https://s3.amazonaws.com/codecademy-content/projects/2/feedster/index.html"). Click on the notification bell at the top right to see the dropdown menu, and click on each post's +1 button.

## Tasks
### 1.
Look at __index.html__. In the `<div class="notification">` section, there are two elements: an `<img>` element and a `<ul class="notification-menu">` element.

When the `<img>` is clicked, we want the `<ul class="notification-menu">` element to appear.

In each `<div class="post">` there is a `<class="btn">` element. When this button is clicked, we want it to turn red.

### 2.
In __app.js__, attach a click event handler to the notification bell image inside the `<div class="notification">` section so that it can respond to a click event.

### 3.
Inside the click event handler, toggle the `<ul class="notification-menu">` element.

### 4.
Attach another click event handler to the +1 button inside a `<div class="post">`.

### 5.
Inside the click event handler, toggle the class `btn-like`.
