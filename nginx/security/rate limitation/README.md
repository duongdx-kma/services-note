
## install siege for testing
```
apt-get install siege
```

## testing with siege:
```
-v, --verbose             VERBOSE, prints notification to screen.

-c, --concurrent=NUM      CONCURRENT users, default is 10

-r, --reps=NUM            REPS, number of times to run the test.

siege -v -r 2 -c 5 https://192.168.56.98/index.html
```

