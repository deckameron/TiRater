TiRater  CommonJS Module ![alt tag](http://www-static.appcelerator.com/badges/titanium-git-badge-sq.png)
=======

Rating module for titanium platform, the module work both Android and iOS

 //-- Usage 
 
 # 1- Copy TiRater.js to app name /app/lib folder
 
 
 # 2- 
 
```javascript

var  rater = require('TiRater');

$.index.addEventListener("open", function(e) {
    rater.initMe(Titanium.App.name,Titanium.App.id);
});

//Call it whenever you want
rater.openRateDialogNow();

```

![alt tag](https://raw.githubusercontent.com/abada/TiRater/master/ios.png)
![alt tag](https://raw.githubusercontent.com/abada/TiRater/master/android.png)

The Original module is https://github.com/raulriera/Rater-Module/

