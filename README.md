import java.util.*;
import java.io.*;
class solution{
static int solve(int x,int p){
int res=x;
while(x>0){
int t=x-(int)(p/100*x)
res=res+t;
x=t;
}
return res;
}
public static void main(string args[]){
Scanner s=new Scanner(System.in);
int x=s.nextInt();
int p=s.nextInt();
System.out.println(solve(x,p));
}
}
