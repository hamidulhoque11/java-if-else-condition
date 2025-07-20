# java-if-else-condition


**1.vowel or consunent**



<div style="overflow-x:auto;">
<pre>
<code>
import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.print("chack vowel or consunent:");
        char letter = sc.next().charAt(0);
        if(letter == 'a'|| letter == 'e'|| letter == 'i'|| letter == 'o'|| letter == 'u'){
            System.out.println(letter+" is vowel");
        }else if(letter == 'A'|| letter == 'E'|| letter == 'I'|| letter == 'O'|| letter == 'U'){
            System.out.println(letter+" is vowel");
        }else{
            System.out.println(letter+" is consunent");
        }
    }
}
</code>
</pre>
</div>





