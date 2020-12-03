- Arrays
	Een array bevat meerdere data
	````
	myArray[1,2,3]
	````
	Een array kan verschillende data bevatten, gescheiden met een comma zoals:
	````
	myArray["dog", 1, 5, "Cat"]
	````
	Een array kan ook 1 of meerdere array's bevatten, gescheiden met een comma
	````
	myArray[[1,2,3],[4,5,6]]
	````
	Een waarde uit een array kan worden uitgelezen
	````
	myArray = myArray[1,2,3];
	console.log(myArray[0]);  // 1
	````
	
	een waarde uit een array kan worden aangepast
	````
	myArray[1,2,3];
	myArray[0] = 5;  // myArray is now [5,2,3]
	````
	Een waarde kan toegevoegd worden aan een array
	````
	myArray[1,2,3];
	myArray.push(4);
	console.log(myArray);
	//myArray: 1,2,3,4;
	````
	
