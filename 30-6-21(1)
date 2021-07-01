import java.util.*;
class replce
{
	static int replaceDigit(int x, int d1, int d2)
	{
		int res = 0, multiply = 1;
		while (x / 10 > 0)
		{
			int remainder = x % 10;
			if (remainder == d1){
				res = res + d2 * multiply;
			}
			else{
				res = res + remainder * multiply;
			}
			multiply *= 10;
			x = x / 10;
		}	
		if (x == d1){
			res = res + d2 * multiply;
		}
		else{
			res = res + x * multiply;	
	}
	return res;
}
public static void main(String[] args)
	{
		Scanner sc = new Scanner(System.in);
		int x=sc.nextInt();
		int d1 = sc.nextInt();
		int d2 = sc.nextInt();
		System.out.println(replaceDigit(x, d1, d2));
		sc.close();
	}
}
