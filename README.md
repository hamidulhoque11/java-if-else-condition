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


**3. Minimum and Maximum**
<div style="overflow-x:auto;">
<pre>
<code>
//Minimum and Maximum chacker 
import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.println("---minimum and maximum number chacker--");
         System.out.print("Enter The First Number:");
        int firstNumber = sc.nextInt();
        
        System.out.print("Enter The Second Number:");
        int secondNumber = sc.nextInt();
        
        System.out.print("Enter The Third Number:");
        int thirdNumber = sc.nextInt();

       
        
        if(firstNumber >= secondNumber && firstNumber >= thirdNumber  ){
            System.out.println(firstNumber+" is Maximum Number");
        }
        
        else if(secondNumber>= firstNumber && secondNumber>=thirdNumber ) {
            System.out.println(secondNumber+" is Maximum Number");
        }
        else if(thirdNumber >= firstNumber && thirdNumber >= secondNumber){
            System.out.println(thirdNumber+" is Maximum number ");
        }
        else{
            System.out.println("Write any 3 value");
        }
        // here is the minimum 
         if(firstNumber <= secondNumber && firstNumber <=thirdNumber  ){
            System.out.println(firstNumber+" is minimum Number");
        }
        
        else if(secondNumber<= firstNumber && secondNumber<=thirdNumber ) {
            System.out.println(secondNumber+" is minimum Number");
        }
        else if(thirdNumber <= firstNumber && thirdNumber <= secondNumber){
            System.out.println(thirdNumber+" is minimum number ");
        }
        else{
            System.out.println("Write any 3 value");
        }
    }
}
</code>
</pre>
</div>


**4.Leap year**
<div style="overflow-x:auto;">
<pre>
<code>
//leap year
import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        Scanner sc= new Scanner(System.in);
        System.out.println("-----Leap year chacker----");
        System.out.print("Enter a year:");
        int year = sc.nextInt();
        if(year%400==0){
            System.out.println("Leap year");
        }else if(year%4==0 && year%100 !=0){
            System.out.println("leap year");
        }else{
            System.out.println("not leap year");
        }
    }
}
</code>
</pre>
</div>

**5. pass or fail**
<div style="overflow-x:auto;">
<pre>
<code>
//pass or fail chack
import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        Scanner sc= new Scanner(System.in);
        System.out.println("-----pass or fail chacker----");
        System.out.print("Enter your marks between 0-100:");
        int marks = sc.nextInt();
        if (marks>=33){
            System.out.println("You are pass!");
        }else if(marks<33){
            System.out.println("you are fail!");
        }else if (marks>100){
            System.out.println("Allart!..enter your marks between 0-100");
        }
    }
}
</code>
</pre>
</div>

**6. value to word/letter**
<div style="overflow-x:auto;">
<pre>
<code>

import java.util.Scanner;

class Main {

    public static void main(String[] args) {
    
        Scanner sc=new Scanner (System.in);
        
        
        System.out.print("Enter any digit between 0-9:");
        int number = sc.nextInt();
        if(number == 0){
            System.out.println("ZERO");
        }else if (number ==1){
            System.out.println("ONE");
        }
        else if(number==2){
            System.out.println("TWO");
        }else if (number == 3){
            System.out.println("Three");
        }else if(number == 4){
            System.out.println("Four");
        }else if(number == 5){
            System.out.println("Five");
        }else if(number == 6){
            System.out.println("six");
        }else if(number == 7){
            System.out.println("Seven");
        }else if(number == 8){
            System.out.println("Eight");
        }else if(number == 9){
            System.out.println("Nine");
        }else{
            System.out.println("please Enter a digit between 0-9");
        }
        }
    
    }

</code>
</pre>
</div>

**7. odd or Even**
<div style="overflow-x:auto;">
<pre>
<code>
import java.util.Scanner;

class Main {

    public static void main(String[] args) {
    
        Scanner sc= new Scanner(System.in);
     int number;
     System.out.println("----Chack Even and odd value ---------");
     System.out.print("Enter any number:");
     number=sc.nextInt();
     if(number % 2==0){
         System.out.println("Even number");
     
     }else {
          System.out.println("odd value"); //we can use another way like "number%2 !=0"
     }
        
        
    }
}

</code>
</pre>
</div>

**8.voter check**
<div style="overflow-x:auto;">
<pre>
<code>

import java.util.Scanner;

class Main {

    public static void main(String[] args) {
    
        Scanner sc= new Scanner(System.in);
        System.out.println("------Chack you are Valid or invalid for voter-----");
        int number;
        String name;
        
        System.out.print("Enter your Name :");
        name=sc.nextLine();
        System.out.print("Enter your age :");
        number=sc.nextInt();
        sc.nextLine();
        if (number>=18){
            System.out.println("Congretulation "+name+" you are valid for voter");
        }else{
            System.out.println("Sorry "+name+" you are Invalid.");
        }
        
        
    }
}
</code>
</pre>
</div>






