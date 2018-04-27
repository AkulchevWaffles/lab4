# lab4
A.  
000000010040110e T _Z7averageif
00000001004010e0 T _Z7averagePdRd

B. 
the output is:
1 4
4 4
4 4
8 4

char a, *pa;
int b, *pb; 
float c, *pc; 
double d, *pd;


the size of char, int, float, double are 1,4,4,8 (bytes) respectively, that's why it is printed like that in the first column of the output
however, the second column prints the size of the pointer*, which has a fixed size depending on the computer, and as for this case, a 32 bit , the size would be 4 byte
