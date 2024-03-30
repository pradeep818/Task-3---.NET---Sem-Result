namespace pradeep;
class System
{
     public static void Main(string[] args)
    {
        int CN, DE, COA, ML,Total,percentage;
        Console.WriteLine("              **Student Details**");
        Console.WriteLine("            ");
        Console.Write("Name : ");
        string name = Console.ReadLine();
        Console.Write("ID :  ");
        string id = Console.ReadLine();
        Console.WriteLine("          ");
        Console.WriteLine("                **Sem Marks**");
        Console.Write("enter the marks of CN : ");
        CN = Convert.ToInt16(Console.ReadLine());
        Console.Write("enter the marks of DE : ");
        DE = Convert.ToInt16(Console.ReadLine());
        Console.Write("enter the marks of COA : ");
        COA = Convert.ToInt16(Console.ReadLine());
        Console.Write("enter the marks of ML : ");
        ML = Convert.ToInt16(Console.ReadLine());
        Total=CN+DE+COA+ML;
        percentage = Total / 4;
        Console.WriteLine("             ");
        Console.WriteLine("            *TOTAL* ");
        Console.WriteLine(Total);
        Console.WriteLine("             *Percentage*");
        Console.WriteLine(percentage+"%");
        Console.WriteLine("        ");
        Console.WriteLine("             ******");
        Console.WriteLine("Name : " + name);
        Console.WriteLine("ID :" + id);
        Console.WriteLine("CN : " + CN);
        Console.WriteLine("DE : " + DE);
        Console.WriteLine("COA : " + COA);
        Console.WriteLine("ML : " + ML);
        Console.WriteLine("Total : " + Total);
        Console.WriteLine("percentage : " + percentage+"%");




    }
}


