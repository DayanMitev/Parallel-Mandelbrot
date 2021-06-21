Parallel-Mandelbrot-Set
A parallel implementation of the Mandlebrot Set construction

The analysis of speedup can be found at docs/, but it is in Bulgarian only

How to run
go run main.go -g=<granularity> -p=<parallelism>, where p is the amount of goroutines that will be started by the program and g is the number of tasks per thread.

More command line parameters
startX - X coordinate of the starting point of complex plane segment
startY - Y coordinate of the starting point of complex plane segment
endX - X coordinate of the ending point of complex plane segment
endY - Y coordinate of the ending point of complex plane segment
