#include <stdio.h>
#include<stdlib.h>
struct node{
    int data;
    struct node *next;
}; struct node *head;

int main()
{
    int n,i;
    printf("Enter No. of nodes in  linked:");
    scanf("%d",&n);
    struct node *a,*b;
        for(i=0;i<n;i++)
    {
        if(head == NULL)
        {
            a = malloc(sizeof(struct node));
            printf("Enter node-1:");
            scanf("%d",&a->data);
            a->next = NULL;
            head = a;
        }
        else
        {
            b = malloc(sizeof(struct node));
            printf("Enter node-%d:",i+1);
            scanf("%d",&b->data);
            a->next = b;
            b-> next = NULL;
            a = b;
            
        }
    }
    struct node *ptr;
    ptr  =head;
    while(ptr!=NULL)
    {
        printf("%d " , ptr->data);
        ptr = ptr->next;
    }

    return 0;
}
// This code was edited by Aditya Raj Sinha
