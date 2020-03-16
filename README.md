# Internal-Shampooing

LOW LEVEL TRAINING: This is just POC - you can add delete update !

Lets Get Closer to The Bytes!
  ---------------------------------------------------------------------
	Some Re and CTF: 
	- Go to microcorruption.com and Sign up.
		- The first steps are easy.. So go fast through that and than the fun begins.
	---------------------------------------------------------------------
	Kernel is Not a bad word! 
		Writing a kernel module:
		(!) Warning : If you decide to do it on  your own computer I wont take the responsibility. I recommend to use a VM or something. Notice the kernel version of course.
			
			1) Please write echo server - "echo server" is a stupid server that returns to the client what the client send to the server. 
				- I recommend to start with writing an echo server in user mode.
			
			client send "Pizza" --> server
			server response "Pizza" --> client
			
			
			2) Clone the kernel SC.
			look around a little bit...
			
			Using kernel modules;
				a) each time the "ls" shell command executed output to the screen "I dont care what is your random string". 
				
				b) choose some process and hide it from ps
			
	---------------------------------------------------------------------
	Scheduling in cpp:
		read the article -	https://probablydance.com/2019/12/30/measuring-mutexes-spinlocks-and-how-bad-the-linux-scheduler-really-is/
		
		You can take a look here too : https://www.geeksforgeeks.org/multithreading-in-cpp/

		Please Write multiclient server that opens for each request a different socket and close it when the client sends FIN. 
		The Server should be stable ;-).
		
		(!) If you have a better idea for multithreading exercise than tell us all!
