# TCL Workshop: From Introduction to Advanced Scripting Techniques in Design and Synthesis

TCL is known as a robust scripting language with programming elements. It is accessible on Windows, Mac OS, and Unix Operating Systems. TCL is used for scripting programs, graphical user interfaces, networking, administration, testing, and Web and desktop applications (GUI).

For Electronic Design Automation (EDA) applications, TCL has emerged as the de facto industry standard embedded command language. TCL is the ideal option if you need to automate repetitive behavior, expand an application’s capabilities, manage many tools with a single script, or develop a unique GUI.







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
