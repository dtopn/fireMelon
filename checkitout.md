Check-points:

1. Register an account and create a repository (repo) on github.com (or gitcafe.com)

2. Push(upload) something into that repo
	A lot of work and efforts can be engaged to acchieve this, and you may spend hours searching and reading. But it really worth it, I mean it. **Searching** is of great importance, no one teached me about these, the only thing I can do is to consult the search engine when the problem arises.
	Note: you can first use the HTTP(S) method to manage your repo, then try to use the SSH method to manage your repo.

	[here(click me)](how2use_git.sh)'s something you can refer to (written by me), but I strongly recommand you just ignore it

3. Know something about markdown, search for a cheatsheet about it. It's really useful sometimes.

4. Learn more about how to use(or write) a standard makefile, it may look like this one, but more refined than this one

```makefile
DEBUG := -g
CC = gcc
CXX = g++
EXECUTABLE = 441
LIBS	=
CFLAG 	= -c -Wall $(DEBUG)
CPPFLAG = $(CFLAG)
LDFLAG = $(LIB)
#LOC	= ./
OBJ 	= 441_1.o 441.o


$(EXECUTABLE): $(OBJ)     
	$(CXX) -o $@ $(OBJ)

.c.o:
	$(CC) ${CFLAG} -c -o $@ $< $(LIBS)

.cpp.o:
	$(CXX) ${CPPFLAG} -c -o $@ $< $(LIBS)

clean:
	@rm *.o
	@rm $(EXECUTABLE)
```


5. If your iPhone is iOS 6.1.2 and below, and you are ok with jailbreaking you device, then jailbreak it. Then ssh into it. Try to get gcc and other UNIX utilities in it. (Hint: you may install aptitude first in cydia. Then the `apt-get` command become available.)

6. Install vim 7.4 in Windows

7. Install cygwin in Windows, and put the path of `bin` in its installation directory into the `PATH` enviroment variable. Thus you may be able to run commands such as `ls` `pwd` in cmd.exe

8. Change your avatar at github.com (fan qiang is required when accessing some web sites)

Good luck, and best wishes.~
