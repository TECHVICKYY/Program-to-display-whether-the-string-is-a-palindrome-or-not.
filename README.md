# Write-a-program-to-accept-a-String-from-the-command-prompt-and-display-whether-the-string-is-a-palindrome or not.
public class A1_Ex3 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		String x = args[0];
		int i=0,j = x.length()-1;
		while(i<j) {
		if(x.charAt(i)==x.charAt(j)) {
		System.out.println(x+" is palindrome!!!");
		System.exit(0);
		}
		i++;
		j--;
		}
		System.out.println(x+" is not a palindrome!!!");
		}
	}
