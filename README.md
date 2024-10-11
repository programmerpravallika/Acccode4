#Given an integer, , perform the following conditional actions:
If n is odd, print Weird
If n is even and in the inclusive range of 2 to 5 , print Not Weird
If  n is even and in the inclusive range of 6 to 20, print Weird
If n is even and greater than 20, print Not Weird
Input Format:-A single line containing a positive integer,n .
Constraints: 1<=n<=100
Output Format:-Print Weird if the number is weird. Otherwise, print Not Weird.
Sample Input :-3
Sample Output :-not weird

n=int(input())
a=[2,3,4,5]
b=[6,7,8,9,10,11,12,13,14,15,16,17,18,19,20]
if (n%2!=0):
    print("Weird")
elif (n%2==0)and n in a:
    print( "Not Weird")
elif (n%2==0)and n in b:
    print( "Weird")
elif (n%2==0)and n>20:
    print("Not Weird")
