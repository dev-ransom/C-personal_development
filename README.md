#include <stdio.h>
// function prototype
int multiply(int numb1, int numb2);
// function declaration/call to the function
int main(){
    int numb1 = 5;
        int numb2 = 6;
	    
	        int product = multiply(numb1, numb2);
		    printf("product of 5 and 6: %d", product);
		        return 0;
			}
			// function definition 
			int multiply(int numb1, int numb2){
			    int product = numb1 * numb2;
			        return product;
				    
				    }
