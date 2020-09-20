# CV
1. *Name*: Polina Zakaryan
2. *Phone number*: +79009017949
3. *Summary*: I am a well-organized, goal-seeking student, who has a quest for new knowledge. My goal is to get a job as a Junior Developer during the year. 
4. *Skills*: HTML, CSS, Javascript
5. *Examples of my code*: 
```
var Calculator = (function() {
	var currentValue = 0;
	return {
		add: function add(x) {
			if ( typeof (x) == "undefined" ) {
				x = 0;
			};
			currentValue = currentValue + x;
			return add;
		},
		subtract: function subtract(x) {
			if ( typeof (x) == "undefined" ) {
				x = 0;
			};
			currentValue = currentValue - x;
			return subtract;
        },
		multiply: function multiply(x) {
			if ( typeof (x) == "undefined" ) {
				x = 0;
			};
			currentValue = currentValue * x;
			return multiply;
        },
		divide: function divide(x) {
			if ( typeof (x) == "undefined" ) {
				x = 0;
			};
			currentValue = currentValue / x;
			return divide;
        },
		getResult: function getResult() {
			return currentValue;
        },
		reset: function reset() {
			currentValue = 0;
			return currentValue;
        }
    }
})();
```
6. *Work experience*: none
7. *Education*: Epam - JavaScript Development (Ryazan)
8. *English*: B2
