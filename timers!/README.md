# A relatively crude timer implenmentation :)

Small example:
```c++
 #include "Timers!"
  
  function testTimer() {
      print("This is a delayed test messaged!")
  }
  
  # timer(<delay>, <repetition>, <function name>) # Make repetitions 0 to repeat it infinite amount of times, function name is the name of the function that should get called
  timer(0.8, 5, "testTimer") # Creates a timer with a delay of 0.8 Seconds, repeats it 5 times and calls the function "testTimer"
```
