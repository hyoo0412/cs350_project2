# CS 350: Project 2: Group 7
Hoyeon, Jack, Mandy, & Rahat

Question(s) to ask Boubin
- for project 2, fork_rc_test.c defines set_sched in the stub function. However, it is also called in the main function, so commenting out the stub function throws an undefined reference for line 48. How do we work around this?
  	- fork_winner() and set_sched() must be implemented in order to properly test for_rc_test
- in part 2 question 3, is the "Write the corresponding system call user space wrapper function" saying to create a transfer_tickets.c file. If so, why would the user have to call the transfer_tickets syscall, shouldn't only processes/scheduler call it since it corresponds to the scheduler stuff?
  	- user space wrapper function aka just add to user.h
  	- no, the .c file is a user program
- If not creating .c file, where do I put the functions?
  	- in user.h --> just make a system call

STEPS TO PUSH/PULL CODE

1. "git add ." BEFORE git pull don't even need to stash (DONT STASH)
2. "git commit" BEFORE git pull
3. "git push" BEFORE git pull
	a) it will tell you if you need to connect and pull
4. if needed, do "git pull"
	a) see by just opening the files
5. if needed, go into merged files and MANUALLY change
6. "git push" with our updates changes, DECONFLCITED CODE now in online git
   	a) everyone should go through this process again,
   	b) but if no changes, should be able to pull
