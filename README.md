PLEASE READ 
This project in not code heavy the the code in here is already in the pintos/src/threads and in pintos/src/devices.
In thread.c 
  1. A single line of code was added t->wake_tick = 0 in init_thread()

In thread.h 
  1. A single line of code was added int64_t wake_tick to struct thread

In timer.c 
  1. Added sleep_list (single line)
  2. Added to wake_tick_less() (multiple lines)
  3. Rewrote timer_sleep() )took out 3 lines and added some different ones)
  4. Updated timer_interrupt() (keep everthing just added on to)

