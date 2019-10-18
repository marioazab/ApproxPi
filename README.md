public class approximatePI
{
    public static void main(String[] args)
    {
        double PI = 1.0;
        int s = 1;
        for (double j = 3.0; j < 10000000; j= j+2)
        {
            if (s % 2 == 0)
                PI = PI + (1/j);
            else
                PI = PI - (1/j);
            s = s +1;
        }
        System.out.println(4*PI);



    }
}
