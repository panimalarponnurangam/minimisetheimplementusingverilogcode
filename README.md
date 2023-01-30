# minimisetheimplementusingverilogcode

AIM:

To  implement the given logic function amd to verify its truth table  in 
quartus using varilog programming.

EQUIPMENTS REQUIRED:
Hard ware-pc,cyclone ||,USBflasher

soft ware-quartus prime

THEORY:
the 3-veriable k-map is represented as an aeeay of eight cells. in this
case,we used A,B,and C for the variable.we can use any letter for the
names of the variables.The binary values of variablesA and B are along
the left side,and the values of C at the top in the same column. 

PROGRAM:

~~~
module mm(a,b,c,y1,y2);
input a,b,c;
output y1,y2;
wire p,r;
and(p,a,y1);
and(r,b,y2);
or(y1,y2,p,r);
endmodule
~~~

RTL:
![Screenshot (103)](https://user-images.githubusercontent.com/121490826/215568772-db9cf379-a98a-4726-96b5-5613488cb9ab.png)



TIMING DIAGRAM:


![Screenshot (102)](https://user-images.githubusercontent.com/121490826/215568894-5072e908-2e6e-49bc-aa91-055dd79c206c.png)


TRUTH TABLE:

![Screenshot (142)](https://user-images.githubusercontent.com/121490826/215569053-b7b172e5-b0ff-49a2-822b-1cb054ca5391.png)



RESULT:
Thus output of the minimise k map are succesfully done.
