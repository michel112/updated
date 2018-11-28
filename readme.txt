Files used: 
--
1. main.py  : contains the main functionality code.
2. unit_test.py : used for the unit testing scenarios.
3. valid.xml: contain the valid xml file used for unit testing.
4. invalid_pom.xml: contain invalid xml file for unit testing.
5. pom.xml: main operating xml file for operations. 
6. Dockerfile: contains the docker setup commands.

--

1. We have create two python file main.py and unit_test.py
	a: Install python following the link 
	b: Navigate to folder containing the code files, 

2. a: Two python files will be there main.py,unit_test.py . In main.py we have specified code for the functionality.
   b: Run the file using 
   python main.py 
   It will output the desired output.

3. For Docker setup: 
	a: Follow the steps to install docker: https://docs.docker.com/install/#support  
	b: In order for creating contatiners, open the power shell (terminal for docker) and navigate to folder containing the code files. After it follow the below commands.
	
	First we use:
	1. docker build -t CONTAINERNAME .
	2. docker run CONTAINERID
	
	