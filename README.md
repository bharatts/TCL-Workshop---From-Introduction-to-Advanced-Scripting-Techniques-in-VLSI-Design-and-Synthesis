# TCL Workshop: From Introduction to Advanced Scripting Techniques in Design and Synthesis

![image](https://github.com/bharatts/TCL-Workshop---From-Introduction-to-Advanced-Scripting-Techniques-in-VLSI-Design-and-Synthesis/blob/main/tcl_result/TCL-Workshop1-2048x1448.jpg)
TCL is known as a robust scripting language with programming elements. It is accessible on Windows, Mac OS, and Unix Operating Systems. TCL is used for scripting programs, graphical user interfaces, networking, administration, testing, and Web and desktop applications (GUI).

For Electronic Design Automation (EDA) applications, TCL has emerged as the de facto industry standard embedded command language. TCL is the ideal option if you need to automate repetitive behavior, expand an application’s capabilities, manage many tools with a single script, or develop a unique GUI.

# Day 1 
Serves as the foundation, introducing you to the core concepts and tasks of TCL. By understanding the fundamentals, you will gain the confidence to tackle any scripting challenge that comes your way. Get ready to witness the power of TCL unfold before your eyes!

# Days 2 and 3 
Immerse you in the art of variable creation and processing constraints. From CSV files to format[1] and SDC, you will learn how to seamlessly convert data, auto-create variables using matrix and arrays, and handle complex processing tasks. Through hands-on demonstrations, you will witness the magic of TCL as it effortlessly manages variables and constraints, empowering you to streamline your scripting workflows.

# Day 4 
You will embark on an exhilarating exploration of advanced scripting techniques. Brace yourself for an introduction to Yosys, a synthesis tool that will revolutionize your scripting capabilities. Unlock the secrets of writing comprehensive scripts, understanding memory module RTL descriptions, and mastering gate level netlist descriptions. With Yosys by your side, you will conquer complex synthesis tasks with confidence and finesse.

# Day 5 
As you delve into the realm of quality of results (QOR) generation. Witness the true power of your scripting prowess as you learn to create high-quality results that surpass expectations. From runtime optimization to precise WNS and FEP analysis, you will unleash the full potential of TCL to generate reports that showcase your expertise.

-----------------------------------------------------------------------------------------------

# Day-1
# Task 
  - Create Shell Script and pass csv file as a argument
  - Invoke TCL script from shell script
# Sub-Task
- Create Variable
- check if directories and files mentioned in csv, exists or not
- Read Constraints file for SDC (Convert csv to .sdc file)
# Results
Results from all scenarios

![image](https://github.com/bharatts/TCL-Workshop---From-Introduction-to-Advanced-Scripting-Techniques-in-VLSI-Design-and-Synthesis/blob/main/tcl_result/day1.jpg)
Invoking shell script
![image](https://github.com/bharatts/TCL-Workshop---From-Introduction-to-Advanced-Scripting-Techniques-in-VLSI-Design-and-Synthesis/blob/main/tcl_result/day1-1.jpg)
Getting help option 
![image](https://github.com/bharatts/TCL-Workshop---From-Introduction-to-Advanced-Scripting-Techniques-in-VLSI-Design-and-Synthesis/blob/main/tcl_result/day1-2.jpg)
Result when wrong csv file is passed


# Day-2 (Variable creation and processing constraints from csv)
Task
- Create variable so that we can access the path, where file is present
- check if directories and files mentioned in .csv, exits or not
- read constraints file for above .csv
- read all files in NetList Dir
- create main synthesis script
# Results
- Checking if files paths exists and readable
  ![image](https://github.com/bharatts/TCL-Workshop---From-Introduction-to-Advanced-Scripting-Techniques-in-VLSI-Design-and-Synthesis/blob/main/tcl_result/Day2_checkfile_ifexistsScreenshot%202023-07-06%20152824.jpg)
- Gives error message if file path dont exists
  ![image](https://github.com/bharatts/TCL-Workshop---From-Introduction-to-Advanced-Scripting-Techniques-in-VLSI-Design-and-Synthesis/blob/main/tcl_result/day2-1.jpg)


# Day3 - (Processing Clock and Input Constraints)

- Sub Task: From CSV to format[1] and SDC processing clock constraints
- Task to differentiating betweens bits and bus port and create sdc format

# Results

- Processing clock ports
  ![image](https://github.com/bharatts/TCL-Workshop---From-Introduction-to-Advanced-Scripting-Techniques-in-VLSI-Design-and-Synthesis/blob/main/tcl_result/Day3_differentiating%20between%20bits%20and%20busesScreenshot%202023-07-07%20003533.jpg)
- Processing input ports as bit and buses
  ![image](https://github.com/bharatts/TCL-Workshop---From-Introduction-to-Advanced-Scripting-Techniques-in-VLSI-Design-and-Synthesis/blob/main/tcl_result/day3_input_ports_readScreenshot%202023-07-07%20125558.jpg)
- Processing output ports as bit and buses
  ![image](https://github.com/bharatts/TCL-Workshop---From-Introduction-to-Advanced-Scripting-Techniques-in-VLSI-Design-and-Synthesis/blob/main/tcl_result/day3_output_port_Screenshot%202023-07-07%20133143.jpg)
- Sample SDC format generated
  ![image](https://github.com/bharatts/TCL-Workshop---From-Introduction-to-Advanced-Scripting-Techniques-in-VLSI-Design-and-Synthesis/blob/main/tcl_result/day3-2.jpg)


  # Day 4 - (Yosys Synthesis tool introduction and hierarchy check)

  - To generated a script which will feed to yosys tool
  - Check if hierarchy is present


  Results

  - check for hierarchy pass
    ![image](https://github.com/bharatts/TCL-Workshop---From-Introduction-to-Advanced-Scripting-Techniques-in-VLSI-Design-and-Synthesis/blob/main/tcl_result/day3-3.jpg)
  - check if hierarchy fails
    ![image](https://github.com/bharatts/TCL-Workshop---From-Introduction-to-Advanced-Scripting-Techniques-in-VLSI-Design-and-Synthesis/blob/main/tcl_result/day3-4.jpg)
  - Generated synthesis script
    ![image](https://github.com/bharatts/TCL-Workshop---From-Introduction-to-Advanced-Scripting-Techniques-in-VLSI-Design-and-Synthesis/blob/main/tcl_result/day3-5.jpg)
  


# Day 5 - (Advanced Scripting Techniques ad Quality of Results Generation)

 - Synthesis main file scripting and output file editing
 - enable procs
 - Generating conf file for OpenTimer to read
 - Generating timing file
 - Printing final result in table format as Quality of Results (QoR)


Results 
- Generated .conf file
  ![image](https://github.com/bharatts/TCL-Workshop---From-Introduction-to-Advanced-Scripting-Techniques-in-VLSI-Design-and-Synthesis/blob/main/tcl_result/conf%20file.jpg)
- Generated timing file
  ![image](https://github.com/bharatts/TCL-Workshop---From-Introduction-to-Advanced-Scripting-Techniques-in-VLSI-Design-and-Synthesis/blob/main/tcl_result/timing%20file.jpg)
- Final Result
  ![image](https://github.com/bharatts/TCL-Workshop---From-Introduction-to-Advanced-Scripting-Techniques-in-VLSI-Design-and-Synthesis/blob/main/tcl_result/Final_Output_Screenshot%202023-07-08%20215103.jpg)


# Acknowledgement
1. Mr. Kunal Ghosh, C0-Founder, VSD Corp. Pvt. Ltd.
2. T R Visruat
