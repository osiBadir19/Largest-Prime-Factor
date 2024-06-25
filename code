#include <stdio.h>

int isPrime(int n){
    for(int i = 2; i <= n; i++)
    {
        if (n%i==0)
            return 0; 
    }
    return 1;
}

int main() {
    int number = 13195;
    int max = 0;
    for (int i=2 ; i <= number; i++)
    {
        // check if the number to divide in prime
        if (isPrime(i) == 0)
        {
            //check if the number divided by prime without remainder
            if (number%i == 0)
            {
                // if true, then check if it greater than the MAX greater factor
                if (i > max)
                    max = i;
                number = number / i;
            }
        }
    }

    printf("the greatest Prime Factor is:\t%d\n", max);
    return 0;
}
