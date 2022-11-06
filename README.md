public class AddNumbers {
public static void main (String[] args) 1
int number = 10;
int sum = addNumbers (number);
System.out.printin ("Sum = " + sum);
}
public static int addNumbers (int num) (
if (num != 0)
return num + addNumbers (num - 1);
else
return num;
}}
