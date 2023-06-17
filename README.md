# Tests for ex4

There is only End to End (file tests) for this exercise.

Credit to [@omrzv](https://www.github.com/omrzv) and [@Amir-Mann](https://www.github.com/Amir-Mann) who created the [original tests for spring 2022 semester](https://github.com/omrzv/matam_tests_spring2022/tree/main/ex4), I adapted them to our semester's exercise :).

## File Tests:
**For the tests to run, make sure to change the witch's force from 11 to 10 and the gremlin's force from 5 to 6!!**

**Also, the tests assume that barfight causes 10 damage and not 8, but as of now the official tests also assume that.**

* Make an executable with the name **FileTester** how ever you choose using the **fileTests/testsMain.cpp** file.
* **fileTests/tester.sh**
* Expect the architecture below. if yours differs, change the files marked *MIGHT NEED CHANGES*
    ./ *terminal / cmd / wsl here* 
    
    ├── fileTests/ 
    
    |   ├── tester.sh    

    |   ├── inFiles/    

    |   |   └── ... 

    |   ├── outFiles/    
    
    |   |   └── ... 
    
    ├── FileTester  
    
    └── ... 
* There are 4030 tests. If you want to run less than that you can change **TESTS_TO_RUN** in *tester.sh* to what ever number you please.
    
* Contains the following files:
    * tester.sh - Runs the the test, *you can change the amount of tests runs in it*
    * testsMain.cpp - The main program (simulates the game and writes the results)
    * inFiles - in files in the format of testXXXX.in and testXXXX.dock
    * outFiles - out files in the format of testXXX.out and after you ran the tests testXXX.result 
