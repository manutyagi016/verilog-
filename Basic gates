# Vlsi-
Project / Programs / Theories / all with output files

module basic_gates(
    input a,b,
    output y1,y2,y3
    );
	 and (y1,a,b);
	 or (y2,a,b);
	 nand (y3,a,b);
	 


endmodule
//TEST BENCH//
`timescale 1ns / 1ps
module basic_gates_tb;

	// Inputs
	reg a;
	reg b;

	// Outputs
	wire y1;
	wire y2;
	wire y3;

	// Instantiate the Unit Under Test (UUT)
	basic_gates uut (
		.a(a), 
		.b(b), 
		.y1(y1), 
		.y2(y2), 
		.y3(y3)
	);

	initial begin
		// Initialize Inputs
		a = 0;
		b = 0;

		// Wait 100 ns for global reset to finish
		#10;
		a = 1;
		b = 0;
		#20;
		a = 1 ;
		b = 1;
		
        
		// Add stimulus here

	end
      
endmodule
