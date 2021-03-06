#Brief Description
This project simulates memory scheduling algorithms like "fifo", "lru" and "2ch-alg".

#Components:
- cs356project2.pdf: problem description and requirement
- project2Intro.pdf: report of project 2
- main.cpp: main function
- directory ./include/: header file and class
- directory ./Testdata/: test data
- directory ./result/: files that record the output. Ignore it if not needed.
- makefile: literally

# Build
Enter
```
	make
```

# Run
Enter
```
	mem‐sim pages quantum pr‐policy trace‐file 
```

where

* **pages** is the number of physical pages
* **quantum** is the number of cycles in a scheduling algorithm
* **pr-policy** is one of "fifo", "lru", "2ch-alg" and indicates which page replacement algorithm to use
* **trace-file** is the name of the scheduling trace file 
