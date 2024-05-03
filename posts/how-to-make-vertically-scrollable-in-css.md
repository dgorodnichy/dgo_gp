+++
sync_date = '2024-05-02 15:16:15 +0300'
title = 'foo'
description = 'bar'
draft = false
tags = ['foo', 'bar']
+++
In order for the scroll to appear, you need to limit its `height` by adding height or `max-height` properties.

```css
.scroll-area {
  overflow-y: auto;
  max-height: 400px;
}
```

If you do not add this, your block will stretch to the entire height.


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/9uxdd7z2ccnh9belnkua.png)


