#include <stdio.h>
#include <stdlib.h>
void minesweeper(int length,int row){
    int count,count1,i=0,r=0,sum[100][100],anwser=0,round=0;
    char input[100][100];
     for(count=0;count<row;count++){
        for(count1=0,i=0;count1<length;count1++){
            //printf("%d lobe\n",i);
           input[i][r]=getche();//if use getch can't see the char but use getche it can see char.
           //printf("%c",input[count1]);
           i++;
        }
         r++;
        printf("\n");
    };
  /* for(count1=0,r=0;count1<=length;count1++,r++){
   for(i=0;i<=length;i++){
     printf("%c",input[i][r]);
    }
    printf("\n");
   }*/
    for(count=0,r=0;count<row;count++){
        for(count1=0,i=0;count1<length;count1++,round++){
            if(input[i][r]=='*'){
              //  printf("%dHello\n",round);
                sum[i][r]='*';
            }
            else if(input[i][r]=='.'){
                    if(input[i][r]=='.'&&i==0&&r==0){//บรรทัดแรก ซ้ายมือสุด
                        if(input[i+1][r]=='*'){
                            sum[i][r]=++anwser;
                        }
                        if(input[i][r+1]=='*'){
                            sum[i][r]=++anwser;
                        }
                        if(input[i+1][r+1]=='*'){
                            sum[i][r]=++anwser;
                    }
                  //      printf("%dHi1\n",round);
                }
                else if(input[i][r]=='.'&&i!=0&&r==0&&i+1!=length){//ตรงกลางบรรทัดแรก
                    if(input[i-1][r]=='*'){
                        sum[i][r]=++anwser;
                    }
                    if(input[i+1][r]=='*'){
                        sum[i][r]=++anwser;
                    }
                    if(input[i-1][r+1]=='*'){
                        sum[i][r]=++anwser;
                    }
                    if(input[i][r+1]=='*'){
                        sum[i][r]=++anwser;
                    }
                    if(input[i+1][r+1]=='*'){
                        sum[i][r]=++anwser;
                    }
                 //   printf("%dHi2\n",round);
                }
                 else if(input[i][r]=='.'&&i+1==length&&r==0){//ขวามือสุด บรรทัดแรก
                        if(input[i-1][r]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i][r+1]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i-1][r+1]=='*'){
                        sum[i][r]=++anwser;
                        }
                      //  printf("%dHi3\n",round);
                    }
                else if(input[i][r]=='.'&&i==0&&r!=0&&r!=row){//บรรทัด>0 ซ้ายมือสุด
                        if(input[i][r-1]=='*'){
                        sum[i][r]=++anwser;
                        }
                         if(input[i+1][r-1]=='*'){
                        sum[i][r]=++anwser;
                         }
                        if(input[i+1][r]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i+1][r+1]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i][r+1]=='*'){
                        sum[i][r]=++anwser;
                        }
                       // printf("%dHi4\n",round);
                    }
                    else if(input[i][r]=='.'&&i!=0&&r!=0&&i+1!=length&&r+1!=row){
                        if(input[i-1][r-1]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i][r-1]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i+1][r-1]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i-1][r]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i+1][r]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i-1][r+1]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i][r+1]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i+1][r+1]=='*'){
                        sum[i][r]=++anwser;
                        }
                       // printf("%dHI5\n",round);
                    }
                    else if(input[i][r]=='.'&&i+1==length&&r!=0&&r!=row){
                        if(input[i][r-1]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i-1][r-1]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i-1][r]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i-1][r+1]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i][r+1]=='*'){
                        sum[i][r]=++anwser;
                        }
                       // printf("%dHi7\n",round);
                    }
                    else if(input[i][r]=='.'&&i==0&&r+1==row){
                        if(input[i][r-1]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i+1][r-1]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i+1][r]=='*'){
                        sum[i][r]=++anwser;
                        }
                       // printf("%dHi6\n",round);
                    }
                    else if(input[i][r]=='.'&&r+1==row&&i+1!=length){
                        if(input[i-1][r]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i-1][r-1]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i][r-1]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i+1][r-1]=='*'){
                        sum[i][r]=++anwser;
                        }
                        if(input[i+1][r]=='*'){
                        sum[i][r]=++anwser;
                        }
                    }
                    else if(input[i][r]=='.'&&i+1==length&&r+1==row){
                        if(input[i][r-1]){
                        sum[i][r]=++anwser;
                        }
                        if(input[i-1][r-1]){
                        sum[i][r]=++anwser;
                        }
                        if(input[i-1][r]){
                        sum[i][r]=++anwser;
                        }
                       // printf("%dHi8\n",round);
                    }
                }
               // printf("answer is %d\n",anwser);
              //  printf("r is %d\n",r);
                //printf("count is %d\n",count);
               // printf("count1 is %d\n",count1);
               // printf("row is %d\n",row);
               // printf("length is %d\n",length);
               // printf("iloop is %d\n",i);
                i++;
                anwser=0;
            }
              r++;
        }
        for(count=0,r=0;count<row;count++){
            for(i=0,count1=0;count1<length;count1++){
                    if(sum[i][r]=='*'){
                    printf("*");
                    }
                    else{
                    printf("%d",sum[i][r]);
                    }
                    i++;
            }
            printf("\n");
            r++;
        }
    }
int main()
{
    int length,row;
    printf("Enter the length :");
    scanf("%d",&length);
    printf("Enter the row :");
    scanf("%d",&row);
    minesweeper(length,row);
    return 0;
}
