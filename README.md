# advanced timer

Example usage:
<<<<<<< HEAD
```julia
=======
```
>>>>>>> 3ce23cc2a76cd7ef13b7989cc3582faf73e100f2
using advanced_timer
timer = class_advanced_timer();
start_advanced_timer(timer);

start_advanced_timer(timer, "add stuff");
x = 0.0;
for i = 1:10000
x += 1.0
end
pause_advanced_timer(timer, "add stuff");

start_advanced_timer(timer, "add stuff");
x += 1.0
pause_advanced_timer(timer, "add stuff");

start_advanced_timer(timer, "times stuff");
x = 1.0;
for i = 1:10000
x *= 2.0;
end
pause_advanced_timer(timer, "times stuff");

start_advanced_timer(timer, "divide stuff");
x = 1.0;
for i = 1:10000
x /= 2.0;
end
pause_advanced_timer(timer, "divide stuff");

pause_advanced_timer(timer)

# print the statistics
print_timer_stats(timer)
```
