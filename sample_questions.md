# CMPSC 101 Midterm Sample Questions

Here are examples of the kinds of questions that might be asked. This is not intended to be a sample exam, it does not include all topics covered on the exam, instead the goal here is to familiarize individuals with the format of the exam. 

1. What is the purpose of a final variable? 


2. Can two different classes contain methods with the same name? Put "X" inside brackets [ ]  of the correct answer.

    - [ ] No
    - [ ] Yes, but only if the two classes have the same name
    - [ ] Yes, but only if the main program does not create objects of both kinds
    - [ ] Yes, this is always allowed

3. Assume there is an array `numbers = new int[42]`. What are the highest and lowest legal array indexes for `numbers`? 

    - [ ] 0 and 41.
    - [ ] 0 and 42.
    - [ ] 1 and 41.
    - [ ] 1 and 42.

4. An unsorted list of 5 elements is given in the following array:

| 15 | 3 | 9 | 24 | 12 |

Without writing any Java code, show each step in the sorting of this array using BubbleSort algorithm. 

5. What is the output to the following program?

``` 
public class Test extends SuperTest {
	public Test() {
		System.out.println("Constructor Test");
	}
	public void act() {
		System.out.println("Action Test");
	}
	public static void main(String [] args) {
		SuperTest test = new Test();
		test.act();
	}
}

public class SuperTest {
	public SuperTest() {
		System.out.println("Constructor SuperTest");
	}
	public void act() {
		System.out.println("Action SuperTest");
	}
}
```

6. [True or False.] If no visibility modifier is specified, methods are private by default. 

Put "X" inside brackets [ ]  of the correct answer.

    - [ ] True.
    - [ ] False.
    
7. Give an example of Polymorphism in Java. 

8. Complete the following Java program as specified in the TODO tasks. No points will be deducted for incorrect syntax, however proper declarations of methods should be followed.

```
public class Patient {
	private int id;
	private String name;
	
	// TODO: write a constructor that accepts and initializes id and name
	
	// TODO: write a method that returns name
}