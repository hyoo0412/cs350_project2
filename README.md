# CS 350: Project 2: Group 7
Hoyeon, Jack, Mandy, & Rahat

Question(s) to ask Boubin
- for project 2, fork_rc_test.c defines set_sched in the stub function. However, it is also called in the main function, so commenting out the stub function throws an undefined reference for line 48. How do we work around this?
- in part 2 question 3, is the "Write the corresponding system call user space wrapper function" saying to create a transfer_tickets.c file. If so, why would the user have to call the transfer_tickets syscall, shouldn't only processes/scheduler call it
  since it corresponds to the scheduler stuff?
- where do I put the functions? 

STEPS TO PUSH/PULL CODE

1. "git stash" to save your changes because they will be overwritten (ONLY overlapping files)
2. "git pull" to absorb everything in git repo in your local clone
3. "git stash show -p" to see 
	a) your added code that got overwritten (in green) 
	b) your other code that got deleted (in red)
4. Manually copy any of this code from terminal into corresponding files
	* now you are all synced up
5. "git push" to store your local repo in main repo
