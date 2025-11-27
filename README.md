include <stdio.h>
int main(){
    int num;
    printf(" enter a number;");
    scanf("%d", num);
    if(num%2==0){
        printf("%dis even number",num);
    }else{
        printf("%dis odd number",num);
    }
    return 0;
}

