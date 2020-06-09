+++
draft = false
date = "2019-12-23T12:09:32+02:00"
publishdate = "2019-12-23T12:09:32+02:00"

title = "Arrays"
description = "How to use arrays in javascript."
summary = "Arrays are used to create lists of data. In JavaScript, an array can contain any type in each position."

tags = [
    "arrays", "javascript"
]

keywords = ['array', 'arrays', 'javascript']

[author]
    name = "Tyler"
    homepage = "/"

[twitter]
    site = "@tylerhq"

[sitemap]
    changefreq = "monthly"
    priority = 0.5
    filename = "sitemap.xml"
+++

# Emoji support

{{% under-title %}}

Arrays in JavaScript allow for lists of data to be organized and used, declared within square brackets, comma separated.
```javascript
let array = ["one", "two", "three"];
```

Each element in the array can be accessed by index, from 0 to length-1.
```javascript
let firstValue = array[0] // "one"
```
