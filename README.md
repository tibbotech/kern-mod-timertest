# kern-mod-timertest
GPIO output + HR timer test

Usage:
# modprobe gpioHRtimer [gpioN=X] [ival=Y]
Where
  gpioN is the the pin number to test as OUT, = 0 by default
  ival is the NANOSECONDS interval for timer, = 1000000000 by default
  
Example:
# modprobe gpioHRtimer gpioN=19 ival=100000
// switch on/off gpio pin #19 every 1/10000 sec
