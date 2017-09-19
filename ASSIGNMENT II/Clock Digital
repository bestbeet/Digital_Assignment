module clock_digtal_counter0 (q,clk,reset);

output [:0] q;
input clk,reset;

T_FF tff0 (q[0], clk, reset);
T_FF tff1 (q[1], q[0], reset);
T_FF tff2 (q[2], q[1], reset);
T_FF tff3 (q[3], q[2], reset);

endmodule

module T_FF(q, clk, reset);
output q;
input clk, reset;
D_FF dff0(q,clk,reset);
not n1 (d,q);

endmodule


module D_FF (q, d, clk, reset);

output q;
input clk, reset;
reg q;

always @(psedge reset or negedge clk)
if (reser)
	q = 1'b0;
else
 q = d ;

endmodule


module clock_digtal_counter1 (q,clk,reset);

output [:0] q;
input clk,reset;

T_FF tff0 (q[0], clk, reset);
T_FF tff1 (q[1], q[0], reset);
T_FF tff2 (q[2], q[1], reset);
T_FF tff3 (q[3], q[2], reset);

endmodule

module T_FF(q, clk, reset);
output q;
input clk, reset;
D_FF dff0(q,clk,reset);
not n1 (d,q);

endmodule


module D_FF (q, d, clk, reset);

output q;
input clk, reset;
reg q;

always @(psedge reset or negedge clk)
if (reser)
	q = 1'b0;
else
 q = d ;

endmodule
