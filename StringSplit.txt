import java.util.Scanner;

public class StringSplit {

	public static void main(String[] args) {
System.out.println("Enter the details of Employee as Firstname,LastName,Role,DOB");
Scanner sc = new Scanner(System.in);
String detail = sc .nextLine();
String arr[]= detail.split(",");
System.out.println("First Name :"+arr[0].toUpperCase());
arr[1] = arr[1].substring(0,1).toUpperCase() + arr[1].substring(1).toLowerCase();
System.out.println("Last Name :"+arr[1]);
System.out.println("Role of Employee :"+arr[2]);
System.out.println("Date of Birth :"+arr[3]);





	}

}
