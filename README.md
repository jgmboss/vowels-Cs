import java.util.Scanner;

public class vowelsandCs 
{
    public static void main (String [] arg) {
        Scanner input = new Scanner (System.in);
        System.out.println ("Please enter a word");
        String word = input.nextLine();
        word.toLowerCase();
        int cont = 0;
        int vow = 0;

        for (int i = 0 ; i < word.length() ; i++)
        {
            if(word.charAt(i) == 'a' ||word.charAt(i) == 'e' || word.charAt(i) == 'i' || word.charAt(i) == 'o' || word.charAt(i) == 'u')
            {
                vow ++;
            }
            else
            {
                cont ++ ;
            }

        }
        System.out.println ("No. of Const  "+ cont + " No. of vowels  " + vow);}
}
