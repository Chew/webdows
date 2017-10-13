![](https://raw.githubusercontent.com/krisdb2009/webdows-docs/master/images/banner.png)



--------------------------------------------------------------------------------





[![](https://raw.githubusercontent.com/krisdb2009/webdows-docs/master/images/docs.png)](https://github.com/belowaverage-org/webdows/wiki) [![](https://raw.githubusercontent.com/krisdb2009/webdows-docs/master/images/demo.png)](http://belowaverage.org/webdows/) [![](https://raw.githubusercontent.com/krisdb2009/webdows-docs/master/images/website.png)](https://belowaverage.org/)





--------------------------------------------------------------------------------





# Webdows is a dynamic window API for the web browser designed to look and feel like Microsoft Windows





--------------------------------------------------------------------------------



# Features

- Simple API

- Built in preloader

- Well documented (Comming soon)

- Supported by Chrome, Safari, Firefox, and Opera.

- Utilizes jQuery

- 99% CSS vector design. _Bitmaps rarely used for styling_

- Customizable themes



# Simple API



## Making a window

```javascript
new explorer.window()
.title('Hello World')
.resize(200, 200)
.callback(function() {
    this.body.html('Test 123');
});
```

![](https://raw.githubusercontent.com/krisdb2009/webdows-docs/master/images/simpleapi1.PNG)

## Creating a context menu

```javascript
new explorer.context()
.append([
    {
       title: 'Hello'
    }, {}, 
    {
       title: 'World',
       callback: function() { console.log('World Clicked'); }
    }
]);
```

![](https://raw.githubusercontent.com/krisdb2009/webdows-docs/master/images/context.png)
