#include<stdio.h>
main(){
  clrscr();
  printf("hello world");
  getch();
}

## Data Types In C:
there is 2 type of datatypes in c.
1) Primary Data types
     - Integer type (int) 2 byte
          - its always take up 4 bytes of memory(32 bits). this means the range of value they can store is necessarily limited to 32 bits worth of information.Range is (2pow31) to (2pow31)-1) upto +-2billion
     - Charector type (char) 1 byte
           - Characters always take up 1 byte of memory(8bits). This means the range of values they can store is necessarily limited to 8 bits worth of information.
           -  Thanks to Ascii, we've developed a mapping of characters like A,B,C etc.. to numeric values in positive side of side of this range. (-128 to +128)
     - Float type (float) 4 byte or 32 bit
          - It will store floating point values (real-number)
     - Double type (double) 8 byte 64 bits.
         - it will also store floating point values(real-number)
     - void type (void) empty datatype
   
   There is 2 more handy data types :
      a) bool #include <stdbool.h>
	  Or use #include<cs50.h> libreary in you project.
	  
	  b)  be sure to #include<cs50.h> atop of program.
2) Secondry data types 
   - Array
   - Pointer
   - Structure
   - enum etc.
   - 
### Modifires: 
A) Sign-> signed-> store+ve & -ve value,unsigned-> only store +ve value.
   - Unsigned double the +ve value it store higher than 2 billion and less than 4 billion.[0-(2pow37)-1]

eg) Unsigned int a;

B) Size-> short , long

eg) int a->2 byte
       Short int a; -> 2 byte
	   long int a; -> 4 byte
       long double a;-> 10 byte
	   
	   
## Operators in C :
- like every other programing language there is also operator in c, we already used one operator that is assignment operator. 
eg:
       Int x=5;
       int y=5;
	 [[c-operators]]  
	Note - for more details about operators click c-operators  [[c-operators]]  