# DECODER2TO4

# Aim:

To simulate and synthesis 2 to 4 Decoder using vivado.

# Apparatus Required:

vivado software.

# Procedure:

STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed. 

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it. 

STEP:5 Select the run simulation adn then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table. 

STEP:7 Select the Implementation in the Sources Window and select the required file in the Processes Window.

STEP:8  Compare the output with logic truth table.


# Truth Table and Circuit Diagram

![image](https://github.com/RESMIRNAIR/DECODER2TO4/assets/154305926/e565d523-f8b2-4e01-8888-0eed4d07ec24)

# Program

module decoder(a,b,d);

input a,b;    

output [3:0]d;

and g1(d[0],~a,~b);

and g2(d[1],~a,b);

and g3(d[2],a,~b);

and g4(d[3],a,b);

endmodule

# Output

![image](https://github.com/Shaiksushma123/DECODER2TO4/assets/159005642/a64f27d5-2908-4996-ba13-8984995b5d1d)


# Result:

Thus the verilog program for 2 to 4 Decoder has been simulated and verified successfully using logic truth table.
