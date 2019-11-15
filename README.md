# **Banana Test** for McGill Fall 2019 COMP 250 Assignment 3 
This Banana Test checks for the correctness and efficiency of your `KDNode.nearestPointInNode` method. For the code to work properly, make sure that your iterator returns all the values (they don't have to be in the right order.) `AnotherA3Tester` (which can be found in the COMP 250 Messenger group chat) can help ensure that your iterator is working properly. 

## Instructions
If you haven't done so yet, register an account for `mimi.cs.mcgill.ca` at https://newuser.cs.mcgill.ca/.

### Step 1. Transfer your `src` folder to your home directory at `mimi.cs.mcgill.ca`
Depending on your operating system, you might want to either `scp -r` or `WinSCP`. If you prefer to mount your `mimi` home folder as a network drive on your Windows Computer, check out [SFTP Drive 2](https://www.nsoftware.com/sftp/drive/) from `/n` software (free for personal use.)

### Step 2. Retrieve the `BananaTest` Java file with `wget`
SSH into `mimi.cs.mcgill.ca`. `cd` to your `src` folder and run the following:
```
wget https://raw.githubusercontent.com/jacobthebanana/McGill-Fall-2019-COMP-250-Assignment-3-Banana-Test/master/BananaTest.java
```

### Step 3. Compile, run, and Profit
Compile using `javac`. Without moving to a different folder folder, run the following:

```
javac BananaTest.java
```

To run the test with default parameters, 
``` 
java BananaTest
```

You may specify the following parameters (all of which are whole numbers) in the command line: 
- `numberOfTests`, 
- `maxNumberOfDatum`, 
- `maxRange`, 
- `dimension`, and 
- `seed`.

```
java BananaTest [numberOfTests] [maxNumberOfDatum] [maxRange] [dimension] [seed]
```

Example: 
```
java BananaTest 100 10000 1000000 5 42
```

## How does this Banana Test compare to `AnotherA3Tester`?
- `AnotherA3Tester` tests for all three methods in the assignment, while `BananaTest` tests only for `KDNode.nearestPointInNode`
- `BananaTest` runs multiple randomized tests and return the average.
- `BananaTest` makes it easy for you to reproduce the results from a particular test by specifying the random generator `seed` and other parameters in the command line.


## Acknowledgements
`BananaTest` would not be possible without the altruistic and innovative work of Zhangyuan Nie, the person behind `AnotherA3Tester`. 

`BananaTest` is created on an Optiplex 990 from Reboot McGill. The Optiplex Tower is proudly housed in the Solin Hall Residence.

## Disclaimer
This program is distributed free of charge, with **absolutely no warranty**. The results might be misleading or inconclusive. Make sure that you review this tester code carefully and understand what it actually does.
