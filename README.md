# SupportTrainingC-
C# Version 

using System;

public class Test
{
	public static void Main()
	{
	//  code goes here
	for(int x=0; x <= 100; ++x) {
    string msg = "";

    if (x%(15) == 0) {
        msg = "SupportTraining";
    } else if (x % 3 == 0) {
        msg = "Support";
    } else if (x % 5 == 0) {
        msg = "Training";
    } else {
        msg = x.ToString();
    }

    Console.WriteLine(msg);
}  // End for
	}  // End Main
}  // End Class
