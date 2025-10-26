# DRIVING TEST GRADE SCORE AS PER AVERAGE SCORE

// Online C compiler to run C program online
#include <stdio.h>

int main() {
int speed,braking,handling,judgement,parking;
char name[30];
float Average;
printf("                            DRIVING TEST SCORE\n");
printf("==============================================================================\n");
printf("Enter driver name:");
scanf("%s",&name);
printf("Enter driving speed score:");
scanf("%d",&speed);
printf("Enter braking score:");
scanf("%d",&braking);
printf("Enter handling score:");
scanf("%d",&handling);
printf("Enter judgement score:");
scanf("%d",&judgement);
printf("Enter parking score:");
scanf("%d",&parking);
Average=(speed+braking+handling+judgement+parking)/5;
printf("Average score:%f\n",Average );
if(Average>90){
               printf("Grade A+: Excellent");
              }
else if(Average>80 && Average<=90){
                                   printf("Grade A:Very Good");
                                  }
else if(Average>70 && Average<=80){
                                   printf("Grade B:Good");
                                  }
else if(Average>60 && Average<=70){
                                   printf("Grade C:Average");
                                  }
else if(Average>50 && Average<=60){
                                   printf("Grade D:below Average");
                                  }
else if(Average<50){
                    printf("Fail");
                  }
 return 0;
}
