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

**2.Small and Capital Letter-**
<div style="overflow-x:auto;">
<pre>
<code>
//Capital or Small
import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.print("chack Capital or Small letter:");
        char letter= sc.next().charAt(0);

       
        
        if(letter == 'A'|| letter == 'B'|| letter == 'C'|| letter == 'D'||
            letter == 'E'|| letter == 'F'|| letter == 'G'|| letter == 'H'||
            letter == 'I'|| letter == 'J'|| letter == 'K'|| letter == 'L'||
            letter == 'M'|| letter == 'N'|| letter == 'O'|| letter == 'P'||
            letter == 'Q'|| letter == 'R'|| letter == 'S'|| letter == 'T'||
            letter == 'U'|| letter == 'V'|| letter == 'W'|| letter == 'X'||
            letter == 'Y'|| letter == 'Z'){
     System.out.println(letter+" is Capital letter");
        }
        
        else if( letter == 'a'|| letter == 'b'|| letter == 'c'|| letter == 'd'||
            letter == 'e'|| letter == 'f'|| letter == 'g'|| letter == 'h'||
            letter == 'i'|| letter == 'j'|| letter == 'k'|| letter == 'l'||
            letter == 'm'|| letter == 'n'|| letter == 'o'|| letter == 'p'||
            letter == 'q'|| letter == 'r'|| letter == 's'|| letter == 't'||
            letter == 'u'|| letter == 'v'|| letter == 'w'|| letter == 'x'||
            letter == 'y'|| letter == 'z') {
         System.out.println(letter+" is Small letter");
        }
        else{
            System.out.println(letter+" Write any latter a-z ");
        }
    }
}
</code>
</pre>
</div>










