# HTML clean blogspot template
When you install a new Blogspot template but it does not display as expected or some redundant widgets appear.
```html
<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='false' b:js='false' b:defaultwidgetversion='2' b:layoutsVersion='3'>
<b:attr name='xmlns' value=''/>
<b:attr name='xmlns:b' value=''/>
<b:attr name='xmlns:expr' value=''/>
<b:attr name='xmlns:data' value=''/>
<head>
<title><data:blog.pageTitle/></title>
<b:skin/>
</head>
<body>
<b:section id='1'/>
</body>
</html>
```
After updating the above code, reload the home page, then you will see the blog is a blank page and no content is displayed.

This basically erases the remaining widget data from the old template. At this point, you can feel secure to install the new template without fear of encountering unexpected errors.

* You can refer to this article from blogger aHí at

https://www.anhhiblog.net/2024/03/huong-dan-cai-dat-template-blogspot-cho-nguoi-moi.html
