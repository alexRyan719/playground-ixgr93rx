# Control Flow
    
    if(score >= 90) {
        return 'A';
    }
    else if(score >= 80) {
        return 'B';
    }
    else if(score >= 70) {
        return 'C';
    }
    else if(score >= 60) {
        return 'D';
    }
    else{
        return 'F';
    }

    // switch_statement1.cpp
#include <stdio.h>

int main() {
   const char *buffer = "Any character stream";
   int uppercase_A, lowercase_a, other;
   char c;
   uppercase_A = lowercase_a = other = 0;

   while ( c = *buffer++ )   // Walks buffer until NULL
   {
      switch ( c )
      {
         case 'A':
            uppercase_A++;
            break;
         case 'a':
            lowercase_a++;
            break;
         default:
            other++;
      }
   }
   