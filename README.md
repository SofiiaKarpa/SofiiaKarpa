-public class Main
{

  public static void main(String[] args) {
    int myArray[] = {3,2,3,1,4,2,8,3};
    int sum = 0;
    for (int i = 0; i < myArray.length; i++) {
      if (myArray[i] > 0) {
        
        
        
        sum += myArray[i];
      }
    }
    
    System.out.println(sum);
    
  }
}
