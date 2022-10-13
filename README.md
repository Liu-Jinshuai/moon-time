# moon-time

### Install

moon-time is a component that converts the solar calendar to the lunar calendar (Chinese lunar calendar), it is very simple to use。

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

	let moonTime = require('calculate')
	
	let moonTimes = moonTime({
	    year:2022,
	    month:10,
	    day:13
	})
	
	console.log(moonTimes);
	
```

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