Notes from StartHere

		/*
		 * 1. Start with the exact class name -- why? Just which class you want 
		 * 2. Give that "instance" of that class a unique name -- why? In case 
		 * you have a bunch of them, like multiple windows
		 * 3. First time, so say "new"
		 * 4. Give the constructor name (obvious), but later we will put parameters 
		 * like players names, difficulty level, .. inside of the ( ).
		 */
		
		// Oh NO!!! DRY -- Do not Repeat Yourself!!!
		
		
Notes from CreateMsg:
	/*
	 * Started with "Greetings" -- but why limit ourselves
	 * We really want to send a msg -- could be Hello!
	 * could be Goodbye! could be Great Job!
	 * So, we want to make our classes "Abstract" (key vocab word)
	 * Ex: Trucks, F150, F250, F350 .... make a class for each? NO WAY!!
	 * Make it "Abstract" (general, generic) -- "Trucks" and then within
	 * Trucks you could make F150, Silverado, Ram, Tundra ....
	 * "Refactor" Rewriting/Reconfiguring the code to make it better (vocab)ex: to CreateMsg instead of Greetings
	 */

	// Make a "constructor" -- a constructor initializes a class
	// that means, what is my initial setup for this class
	
	// to make a constructor:
	// 1. public -- so other classes can get to it
	// 2. exact same name as the class 
	// 3. () if you want to pass any info in like player names
	// 4. { ... code goes here ... }
	// 5. NO RETURN TYPE
	
	
Notes from GuessNumber:
	/*
 	* vocab: " Encapsulation" means keep all -related- code in a 
 	* single class, do not spread our things all over the place!
 	* Old days "Spaghetti" code, couldn't trace anything!!
 	* Now: Go to one class, find all -related- code in that class - easy!
 	* fast! efficient!
 	*/
	//"field" variables -- put ALL your vars up top
	// Making it super easy to change things
	// as you keep figuring out the best way for your code to work

	
	// next, constructor(s) -- you can have more than one constructor 
	// that would be called a constructor "stack"
	/*
	 * 4 types of loops
	 * 1. for loop if you know how many times to loop
	 * 2. while loop if you don't know how many loops ahead of time
	 * 3. do- while variation of above
	 * 4. enhanced for loop for arrays
	 */
	Inclusive for the first number,
	Exclusive for the second number to avoid overlapping numbers
	when you stack these; ex:
	
	0-10, 10-20, 20-30 is a possible stack; you don't want duplicate at 10, and 20
	
	//test
		for (int i = 0; i < 100; i++) {

			System.out.println(i + ", rand = " + (rand.nextInt(upperLimit) + lowerLimit) );

	 
	VOCAB
	 // guessOne is called an "instance" of this class (vocab)
	 // a class instance is also sometimes called an object of that class
		
	 //So, we want to make our classes "Abstract" (key vocab word)
	 //Make it "Abstract" (general, generic)
	 //Abstract classes are classes that contain one or more abstract methods
	 
	 // Make a "constructor" -- a constructor initializes a class
	// that means, what is my initial setup for this class
	 
	 //Create a "method" (vocab)
	//scope return type name(lower case)  pass parameters
	
	
	//vocab: " Encapsulation" means keep all -related- code in a 
 	//single class, do not spread our things all over the place! 
 	
 	//"field" variables -- put ALL your vars up top
 	
 	// next, constructor(s) -- you can have more than one constructor 
	// that would be called a constructor "stack"
	
	Inclusive for the first number,
	Exclusive for the second number to avoid overlapping numbers
	
		// "Field" Very Important is "Scope"
	// "Public" means any other class has access; usually BAD!
	// "Private" means only used inside of this class; usually this is very good!
	// "Protected" means can be used by any other class in this package
	// default is Protected
	
	// a getter is a reader and a setter is a writer
	
	The static keyword in Java means that the variable or function is shared between 
	all instances of that class as it belongs to the type, not the actual objects themselves
	 