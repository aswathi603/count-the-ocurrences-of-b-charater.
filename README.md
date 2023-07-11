# count-the-ocurrences-of-b-charater.

input 

    #include<stdio.h>
    int main()
    {char s[23];
	   int i,count=0;
	   printf("Enter the string:");
	   gets(s);
	   for (i=0;i<23;i++)
	  {
			  if(s[i]=='b'||s[i]=='B')
			  {
				  count++;
			  }	
	  }
	  printf("Frequency of 'b' is:%d\t",count);
    }


output

      Enter the string:Black boat near by sea.
      Frequency of 'b' is:3
