# mehranbarati
using System;
class program 
{
    public static void Main(string[] args) {
        string y = Console.ReadLine();
        double z = Convert.ToDouble(y);

        calcutFunction(z);
        Console.WriteLine("----- Created By Mehran Barati -----");
    }

    private static void calcutFunction(double z) {
        double pow2 = Math.Pow(z, 2);
        double pow3 = Math.Pow(z, 3);
        Console.WriteLine("Power 2 : " + pow2 + " ,power 3 " + pow3);
    }
}
