# moon-time

moon-time is a component that converts the solar calendar to the lunar calendar (Chinese lunar calendar), it is very simple to use。

### Install

```javascript
    npm install moon-time
```

```javascript
    let moonTimes = moonTime({
        year,
        month,
        day
    })
```

### npm way

```javascript

    let moonTime = require('moon-time')
    // import moonTime from 'moon-time'
    
    let moonTimes = moonTime({
	 year:2022,
	 month:10,
	 day:13
    })
	
    console.log(moonTimes);
	
```

The previous version used：let moonTime = require('calculate');
In order to unify the naming, it is now changed to "moon-time", the previous "calculate" naming is still available, but subsequent updates will occur at "moon-time", it is recommended to use "moon-time"

### javascript way

```javascript
<body>
    <script src="./calculate"></script>
    <script>
        let moonTimes = moonTime({
	    year:2022,
            month:10,
            day:13
        })
        
        console.log(moonTimes);
    </script>
</body>
```