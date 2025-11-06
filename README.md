#include <stdio.h>
int main(){
    int a;
    printf("Enter 0 to turn off the heataer or 1 to turn on the heater \n");
    scanf("%d",&a);
    if(a==1){
        printf("Heater is turned on");
    }
    else {
        printf("Heater is turned off");
    }
    return 0;
}
