# Stack Machine
A stack machine which allows the user to push and pop integers onto a stack. Takes one command line argument, which is the number of commands the user wants to execute. Valid commands are "push <n>", where n is an integer, and "pop". The stack starts with an initial size of 10, but if the user exceeds this number then the stack doubles in capacity. If the user pops when the structure is empty, a -1 is returned.