#include<stdio.h>
#include<stdlib.h>
#define SIZE 5

int stack[SIZE],top=-1;

void push (int element){
    if(top == SIZE-1){
        printf("Stack overflowing unable to push %d",element);
    }else{
        top++;
        stack[top]= element;
    }
}
void pop(){
    if (top == -1){
        printf("stack underflow no element to pop");
    }else{
        printf(" %d poped from stack",stack[top]);
    }
}
void display(){
    if (top == -1){
        printf("Stack is Empty");
    }else{
        printf("Stack element :");
        for(int i=top ; i>=0 ; i--){
            printf("%d ",stack[i]);
    }
    }
}
int main(){
    int choice,element;
    while(1){
        printf("1.push\n2.pop\n3.display\n4.exit\n");
        printf("Enter your choice : ");
        scanf("%d",&choice);

        switch(choice){
            case 1:
            printf("Enter element to push : ");
            scanf("%d",&element);
            push(element);
            break;

            case 2:
            pop();
            break;

            case 3:
            display();
            break;

            case 4:
            exit (0);

            default:
            printf("Invalid choice, please try again");
        }
}
        return (0);
}
