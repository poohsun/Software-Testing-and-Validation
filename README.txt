Steps to compile and run programs:
1. Move "branchcoverage.py" and "stmtcoverage.py" from Coverage folder to benchamarks folder.
2. After that run the commands:
	python stmtcoverage.py <filename>  
	python branchcoverage.py <filename>
   where the filename is tcas, totinfo, replace, schedule, schedule2, printtokens, printtokens2
3. Running the above 2 commands will generate test suites for statement and branch coverage in combination with random, total and       additional prioritization.
4. Move "faultfound.py" to the benchmarks folder.
5. Run the command python 
	faultfound.py <filename> <testsuite filename>
   where the filename is tcas, totinfo, relpace, schedule, schedule2, printtokens, printtokens2 and the testsuite filename is    randomstmttestsuite.txt, randombranchtestsuite.txt, totalstmttestsuite.txt, totalbranchtestsuite.txt,    addstmttestsuite.txt,addbranchtestsuite.txt.
6. Running the above command indicates the faults that are exposed in the testsuites created.