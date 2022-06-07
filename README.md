# number-ranges-in-btw-2-numbers 
#include <stdio.h>
int main() {
    int a,b,c;
    scanf("%d",&a);
    for(int i=0;i<a;i++){
        scanf("%d%d",&b,&c);
        if(c>=b & c<=b+200){
            printf("Yes the number ranges in between those two\n");
        }
        else{
            printf("No\n");
        }
    }
    return 0;
}
