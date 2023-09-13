# effective-doodle
{         
    public static void Main()
//This is a name from recommendation. Here is my 1st year student activity as a Computer Science student. I first started to input name and age. In few years hoefully it would be helpfull to a cs student like me. Language: C#
	
 
 
 
 
 
 //ToGet:Name
        Console.WriteLine("What is your name?");
		string name=Console.ReadLine();
		Console.WriteLine("Hello " + name " this is a SURVEY PROJECT kindly answer the following questions:");	
		//To:Continue 
		Console.WriteLine("PRESS ENTER FOR THE NEXT QUESTION");
		Console.WriteLine();
		Console.ReadKey();
  
		//ToGet:Age
		Console.WriteLine("What is your age?");
		int age=Convert.ToInt32(Console.ReadLine());
		Console.WriteLine("You are " + age " years old!");
		Console.WriteLine();
		
	    //To:Continue 
		Console.WriteLine("PRESS ENTER FOR THE NEXT QUESTION");
		Console.WriteLine();
		Console.ReadKey();
		
		//ToGet:Grade
        Console.WriteLine("What is your grade level?");
		string grade=Console.ReadLine();
		Console.WriteLine("You are a " + grade " student");
		Console.WriteLine();
		
		//Thank you
		Console.WriteLine("THANK YOU FOR ANSWERING OUR QUESTIONS");
		Console.ReadKey();

