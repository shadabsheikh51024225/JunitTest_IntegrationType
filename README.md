# JunitTest_IntegrationType
This Project explain about JunitTest Integration, Method Flow type, Control over the Code execution , test categories etc.
This wil cover Following topics:- 




1. How to Configure JUnit in Android Studio.







2. JUnit Annotations:-

- startUp()
- setUpTest()
- firstTest()
- teardownTest()
- setUpTest()
- secondTest()
- tearDownTest()
- End()







3. JUnit Assertions:-

1. assertTrue([message,] boolean condition) - Checks that the boolean condition is true.
2. assertFalse([message,] boolean condition) - Checks that the boolean condition is false.
3. assertEquals([message,] expected, actual) - Tests that two values are the same. Note: for arrays the reference is checked not the content of the arrays. 
4. assertEquals([message,] expected, actual, tolerance) - Test that float or double values match. The tolerance is the number of decimals which must be the same.
4. assertNull([message,] object) - Checks that the object is null. 
 
 
 
 
 
 
 
 
 
 

4. JUnit Test Suit and Test Execution Order:-

    FirstTestClass.class,
        SecondTestClass.class,
                ThirdTestClass.class 
                
                
           
           
           

5. JUnit Parameterized Tests.

6. JUnit Categories
