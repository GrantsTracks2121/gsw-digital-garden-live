---
title: A new file with wikilinks
---

## Get Ready for this:
Here's a picture inserted with wikilink format
And NOPE adding this image using the wikilink format doesn't work. So simply go standard. You can test all the options you worked up for MkDocs here too.

![[download.png]]

Here's the same images above in standard markdown image format:
![](assets/download%201.png "Here's the Alt text")

THIS code works in Jekyll!!

It like this:

```
![](assets/download%201.png "Here's the Alt text"){: width="300px" style="float:right; vspace:20px; hspace:20px" }
```


![](assets/download%201.png "Here's the Alt text"){: width="300px" style="float:right; vspace:20px; hspace:20px" } Look Mom! I can align right!!

Phasellus eu erat quis augue placerat porttitor. Curabitur lobortis congue dolor ac maximus. Nullam porttitor enim felis, quis pretium tellus vehicula non. Aliquam venenatis varius eleifend. Morbi odio ex, pellentesque sed convallis ut, auctor vitae risus. Aliquam at nulla ac arcu mollis fringilla. Aliquam nisi est, vehicula quis enim sit amet, efficitur dictum mauris. 
Nam a. sem augue. Phasellus eu erat quis augue placerat porttitor. Curabitur lobortis congue dolor ac maximus. Nullam porttitor enim felis, quis pretium tellus vehicula non. Aliquam venenatis varius eleifend. Morbi odio ex, pellentesque sed convallis ut, auctor vitae risus. Aliquam at nulla ac arcu mollis fringilla. Aliquam nisi est, vehicula quis enim sit amet, efficitur dictum mauris. 

and links to other files:
- [[your-first-note]]
- [[move your body every day]]
- [[consistency]]