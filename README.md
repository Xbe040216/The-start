#include<stdio.h>

int calculate(int dad, int mam);
int main()
{
    int m_dad;
    int m_mam;
    int result;

    printf("爸爸的身高 \n");
    scanf_s("%d", &m_dad);
    
    printf("妈妈的身高\n");
    scanf_s("%d", &m_mam);

    result = calculate(m_dad, m_mam);
    printf("孩子的身高是：");
    printf("%d", result);
     return 0;
}    
int calculate(int dad,int mam)
{
    int result = (dad + mam) * 0.50;
    return result;
}



