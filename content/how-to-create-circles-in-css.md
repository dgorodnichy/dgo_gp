+++
title = "How to create circles in CSS"
description = "Let's look at a few tricks in CSS able to create basic shapes like circles.    &lt;div..."
created_at = "2022-08-16T12:14:22Z"
edited_at = "2022-08-17T11:57:13Z"
sync_date = "2024-05-03T10:58:36Z"
draft = false
tags = ["css", "html", "devops"]
+++
Let's look at a few tricks in CSS able to create basic shapes like circles.
```html
<div class="circle"></div>
```

## Border-Radius
For this case need to use the border-radius property and set the value to 50%. Then combine the height and width properties with a matching value.
```css
.circle {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  background: lightgreen;
}
```
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/f8wphtna4iy825wyscnw.png)

## Circle()
In this, the circle is created using the shape-outside property. You must also apply a clip-path with the appropriate property to make the circle appear.
```css
.circle {
  width: 100px;
  height: 100px;
  clip-path: circle();
  shape-outside: circle();
  background: yellow; 
}
```
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/xug5rpk5y88kwbg8z98d.png)
  