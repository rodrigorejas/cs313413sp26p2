COMP 313/413 Project 2 Report Template

TestList.java and TestIterator.java

	TODO also try with a LinkedList - does it make any difference?

		Answer: Changing from an ArrayList to a LinkedList did not make a difference for any of the tests.

TestList.java

	testRemoveObject()

		list.remove(5); // what does this method do?

			Answer: This method removes the element at index 5.

		list.remove(Integer.valueOf(5)); // what does this one do?

			Answer: This method removes the first object with value 5 from the list.

TestIterator.java

	testRemove()

		i.remove(); // what happens if you use list.remove(77)?

			Answer: If that is used then it shows a exception error.

TestPerformance.java

	State how many times the tests were executed for each SIZE (10, 100, 1000 and 10000)
	to get the running time in milliseconds and how the test running times were recorded.
	These are examples of SIZEs you might choose, you can choose others if you wish.

	SIZE 10
			         #1  #2  #3  #4  #5   	
        testArrayListAddRemove:  61  103 107 98  98   
        testLinkedListAddRemove: 134 40  48  49  45
	testArrayListAccess:     37  27  24  40  30 
        testLinkedListAccess:    23  19  19  22  22 

	SIZE 100
				 #1  #2  #3  #4  #5  	
        testArrayListAddRemove:  131 126 137 142 147  
        testLinkedListAddRemove: 50  41  51  38  46
	testArrayListAccess:     34  27  44  23  36 
        testLinkedListAccess:    41  38  42  37  41 

	SIZE 1000
				 #1  #2  #3  #4  #5    	
        testArrayListAddRemove:  406 400 467 480 448  
        testLinkedListAddRemove: 48  60  40  46  46 
	testArrayListAccess:     34  41  29  31  33 
        testLinkedListAccess:    505 495 414 417 393 
	SIZE 10000
				 #1   #2   #3   #4   #5  
        testArrayListAddRemove:  3375 3305 48   3270 3820 
        testLinkedListAddRemove: 47   46   50   46   46
	testArrayListAccess:     28   31   38   37   29 
        testLinkedListAccess:    4746 4945 6106 4822 5927

	listAccess - which type of List is better to use, and why?

		Answer: ArrayList is better to use because of the run time. 

	listAddRemove - which type of List is better to use, and why?

		Answer: LinkedList is better to use because of add or remove can be done easily without shifting elements.