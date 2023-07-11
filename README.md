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
  
