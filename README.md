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
	    2022,
	    10,
	    13
	})
	
	console.log(moonTimes);
	
```

### javascript way

```javascript
<body>
    <script src="./calculate"></script>
    <script>
        let moonTimes = moonTime({
			2022,
			10,
			13
        })
        
        console.log(moonTimes);
    </script>
</body>
```