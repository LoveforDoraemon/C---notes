# tips

## 5.24

1. ```c
   // dynamic array
   #include<stdlib.h>
   
   	int len;
       int *arr=NULL;
       arr=(int *)calloc(n,sizeof(int));
       if(arr==NULL)exit(1); // must check
       arr[0]=...
       ...
       free(arr); // free the memory
   ```

2. ```c
   // timekeeper
   #include<time.h>
   
   int begin,end;
   begin=clock();
   ...
   end=clock();
   
   time=end-begin; // ms
   ```

## 5.26

1. ```c
   // there is no need to initialize a pointer when definite
   // where the pointer must be pointed at somewhere before being used!!!
   // for example
   char *s[1000];
   char s[1000][1500];
   // it's quite different!
   ```

## reference

1. https://blog.csdn.net/jianbai_/article/details/109728592
2. https://www.cnblogs.com/wqaz-0-1-2-3/p/13308764.html