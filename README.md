import java.util.Scanner; 

public class ProblemFour {
   
   public static int findNextCharInString(String str, int starIndex, char target){
    for (int i = starIndex; i < str.length(); i++){
        if (str.charAt(i) == target){

        }
    }
    return -1;
   }
   
   public static void main(String[] args) {
      Scanner scnr = new Scanner(System.in); 
      String inputString; 
      int startIndex; 
      char searchChar; 
      
      inputString = scnr.next(); 
      startIndex = scnr.nextInt(); 
      searchChar = scnr.next().charAt(0); 
      
      System.out.println(findNextCharInString(inputString, startIndex, searchChar)); 
      System.out.println(result);
   }
}
