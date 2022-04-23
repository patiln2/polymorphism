using System;
namespace CSharp_Shell
{	
	public class program
	{
		void add(int a,int b)
		{
			int c=a+b;
			Console.WriteLine("Addition of a and b="+c);
		}
		void add(int a,int b,int c)
		{
			int c1=a+b+c;
			Console.WriteLine("Addition of a.b and c="+c1);
		}
		public static void Main(string[] args)
		{
			program p=new program();
			p.add(10,20);
			p.add(10,20,30);
			Console.ReadLine();
		}
		}
	}
