# A relatively crude timer implenmentation :)

Small example:
```
#include "Timers!"

function test(Self:table) {
    print("This is a delayed test messaged!")
}

print("Test message in 5 seconds!")
timer(5, 1, "test")
```
