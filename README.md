- 👋 Hi, I’m @Skmudd
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

#include <stdio.h>  
  
int main()  
{  
    int n;  
    printf("Enter the number of rows");  
    scanf("%d",&n);  
    for(int i=n;i>=1;i--)  
    {  
        for(int j=1;j<=i-1;j++)  
        {  
            printf(" ");  
        }  
        for(int k=1;k<=n;k++)  
        {  
           if(i==1 || i==n || k==1 || k==n)  
            printf("*");  
            else  
            printf(" ");   
        }  
        printf("\n");  
    }  
    return 0;  
}  





<!---
Skmudd/Skmudd is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
