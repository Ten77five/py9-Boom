# py9-Boom
Ten 77 five

#include <iostream> #include <ctime> #include <cstdlib> using namespace std; int main() { //declaring numbers int i,j; //set the seed srand ( (unsigned) time (NULL)); // generate 10 random numbers for(i=0;i < 10; i++) { //generte actual random number j = rand(); cout << "Random Number : "<< j <<endl; } return(0); }//end of main() //end of program
//bitwise OR operatio
z = x | y; cout << "z = x| y = " << z <<endl; //bitwise NOT operation cout << "z = " << z << " ~(z) = " << ~(z) << endl; //Print message to user about program. cout << "===Shift Operations allowed on integers.===\n"; cout <<"\t\tx = 2 = 0010\n\t\ty = 10 = 1010\n\t\tz = 0 = 0000\n"; //left shift operation z = x << 2; cout << "z = x << 2 = " << z << endl; //bitwise OR operation z = y >> 2 ; cout << "z = y >> 2 = " << z << endl; } //end of program.
