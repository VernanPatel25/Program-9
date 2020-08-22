public class Q3
{
    public static void main(String args[])
    {
        int max = 100; 
        int min = 1; 
        int range = max - min + 1; 
       for(int i=1;i<21;i++)
        {
             int rand = (int)(Math.random() * range) + min; 
            System.out.println(rand);
        }
