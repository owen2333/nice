*	A导包
	import java.util.Scanner;
	B创建磁盘录入对象
	Scanner sc = new Scanner(System.in);
	C通过对象获取数据
	int x = sc.nextInt();
*/
import java.util.Scanner;
class ScannerDemo{
	public static void main(String[] args){
		Scanner sc = new Scanner(System.in);//创建一个录入对象
		System.out.println("请输入一个数据");
		int x = sc.nextInt();//String s = sc.nextLine();
		System.out.println("输入的是"+x);
}
}
