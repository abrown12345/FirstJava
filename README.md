# FirstJava
import java.util.Scanner;

public class FirstJava {

	public static void main(String[] args) {
	try (Scanner my_scanner = new Scanner(System.in)) {
		int alfredo, bacon, total; 
		System.out.println("How many cups of alfredo do you want?");
		alfredo= my_scanner.nextInt(); 
		System.out.println("How many cups of bacon do you want?");
		bacon= my_scanner.nextInt();  
		total= alfredo + bacon; 
		System.out.printf("Your measurements for desired bacon alfredo is as follows in cups ");
		System.out.println(total);
	}
			

	}

}
