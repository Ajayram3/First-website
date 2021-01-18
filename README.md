#include<stdio.h>
int main(){
    int Secretnumber=5;
    int Guess;
    int Totalguess=1;
    printf("Enter a Number:");
    scanf("%d",&Guess);
    while(Guess!=Secretnumber && Totalguess<=3)
    {
        printf("Enter a Number:");
        scanf("%d",&Guess);
        Totalguess++;
    }
    if(Totalguess<=3){
        printf("You Win");
    }else{
        printf("You Lose")
    }
    return 0;
}
