# Warm Up!

## Translate JS to Python

Based on what you learned from over the weekend, Google and the [Python docs](https://docs.python.org/3/) translate the following three functions form JS to Python. Put them in a file and test them by running `python filename.py` in your terminal. 

#### FizzBuzz

```js
const fizzBuzz = () => {
	for (var i=1; i <= 100; i++) {
	    if (i % 15 == 0)
	        console.log("FizzBuzz");
	    else if (i % 3 == 0)
	        console.log("Fizz");
	    else if (i % 5 == 0)
	        console.log("Buzz");
	    else
	        console.log(i);
	}
}
```


#### Favorite Drink (from w3Schools)

```js
const favDrink = () => {
	var text;
	var favDrink = prompt("What's your favorite cocktail drink?");
	switch(favDrink) {
	    case "Martini":
	        text = "Excellent choice! Martini is good for your soul.";
	        break;
	    case "Daiquiri":
	        text = "Daiquiri is my favorite too!";
	        break;
	    case "Cosmopolitan":
	        text = "Really? Are you sure the Cosmopolitan is your favorite?";
	        break;
	    default:
	        text = "I have never heard of that one..";
	        break;
	}
}
```

#### OOPython (from MDN)

```js
const createNewPerson = (name) => {
  var obj = {};
  obj.name = name;
  obj.greeting = function() {
    alert('Hi! I\'m ' + this.name + '.');
  };
  return obj;
}

var salva = createNewPerson('Salva');
salva.name;
salva.greeting();
```
