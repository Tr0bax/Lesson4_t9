# Lesson4_t9
public class delenieNaDva {
  public static void main(String args[]) {
    int numb1;
    System.out.println("Введите число: ");
    Scanner input = new Scanner(System.in);
    numb1 = input.nextInt();
    if ( numb1 % 2 == 0 )
        System.out.println("Число четное");
     else
        System.out.println("Число нечетное");
  }
}
