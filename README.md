# array
sample array program
class arraytest
{
public static void main(String[] args)
{
String names[]={"jai","manoj","ram","prabhu","raj"};
for(int x=2;x<5;x++)
{
System.out.println("the value of index "+x +"is:"+names[x]);
}
System.out.println(names[4]);
System.out.println(names[7]); //array index out of boundsException
}
}




FOR EACH

class arrayname
{
public static void main(String []args)
{
String subjects[]={"eng","mat","tamil","social","science","computer"};
for(String x:subjects)
{
	if(x=="social")
		continue;
System.out.println("Subjects are :"+x);
}
}
}
