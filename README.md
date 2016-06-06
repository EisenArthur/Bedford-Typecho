# BedFord for Typecho
A light and elegent theme ported from Farbox by Cho.
https://github.com/pagecho/Bedford

## Important
* Fix CSS missing problem. Sorry for the inconvenience. Please re-download the files.
* Fix Page Nav style missing problem. As for padding problem of element `ul`, `h2`, `blockquote` and so on, I'm afraid it's because the author forgot about it in his style sheet.

Add the following code to your `static/style.css` to fix the padding problem if you like.
```
.post-content h1,.post-content h2,
.post-content h3,.post-content h4,
.post-content h5,.post-content h6,
.post-content ul,.post-content ol,
.post-content blockquote {
    max-width: 750px;
    margin-left: auto !important;
    margin-right: auto !important;;
}
li p {
    padding-left: 0 !important;
    margin-bottom: 0 !important;
}
```
And for `code` and `pre`, just add `p` tag for each line.

## ScreenShot
![ScreenShot](https://raw.githubusercontent.com/LjxPrime/bedford/master/screenshot.png)

## Note
* You can replace the image file @ `static/avatar.jpg` to change your own avatar.
* For archive page, just publish a new page using the corresponding template with a post slug of `archive`.
* For about page in sidebar, just publish a new page with a post slug of `about`.
