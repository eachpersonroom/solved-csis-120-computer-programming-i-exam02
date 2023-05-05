Download Link: https://assignmentchef.com/product/solved-csis-120-computer-programming-i-exam02
<br>
[01] Write a code fragment that accomplishes the following:

1) Asks the user to enter student emails one name at a time.

2) If an email does NOT contain ‘@’ it prints the student sequence number and the word “invalid”.

3) It stops if the user enters “end”.

4) Prints total number of students with invalid emails.

[02] Implement question [01] as a method that does all stated steps, accepts no parameters and returns number of invalid emails.

[03] Convert the following for-loop into a while-loop and write its output:

double sum = 0;

for(int k=16; k 0; k /= 2){

sum += k;

sop(k);

}

sop(sum);

double sum = 0;

int k=16;

while( k 0){

sum+=k;

Sop(k)

k/=2

}

[04] Find and fix all errors in the following code fragment:

The code is supposed to read number of student first names and print the first and last letters of each name. The code quits when the user enters “done”.

String name = “”;

Scanner in = new Scanner(System.in);while( name != “quit” ){

sop(“enter next name = ” );

in.nextInt() = name; // ERR

name = in.nextInt();

sopl(name(0) + “:” + name(10));

sopl(name.chaAt(0) + “:” + name.chaAt( name.length()-1) )

}

[05]  Convert question [03] to a do-loop.

double sum = 0;

int k=16;

do{

sum+=k;

Sop(k)

k/=2

} while( k 0);

[06]  Write a code fragment that does the following:

1) Calculates multiplication table of the size (10 x 10)

2) Prints the generated table in (1) above, each row in a separate line

3) Finds and prints the average of the entire table.

[07]  Based on question [06], Write a method that satisfies the following:

1) Returns a double type

2) Accepts two parameters as r: number of rows, c: number of columns

3) Calculates multiplication table of the size specified in (2) above

4) Prints the generated table in (3) above, each row in a separate line

5) Finds and returns the average of the entire table.

[08] Write the output of the following code:  10 2 1 2

public static void main(String[] args) {

fun2(10);

fun2(20);

sop(fun1(10));

sop(fun1(20));

}

public static int fun1(int x) {

for (int i = 0; i &lt; 3; ++i) {

x /= 2;

}

return x;

}

public static void fun2(int x) {

if (x 10) {

sop(fun1(x));

} else {

sop(x);

}

}