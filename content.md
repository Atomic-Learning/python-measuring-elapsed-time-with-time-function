By calling `time.time()` before and after a block of code and subtracting one value from the other, you can measure how long the code took to execute:

```py-cell
import time

start_time = time.time()
# Code to be timed goes here
for i in range(1000000):
    x = i
end_time = time.time()
elapsed_time = end_time - start_time

print(elapsed_time)
```