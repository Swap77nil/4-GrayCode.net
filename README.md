# GrayCode.net

using System;<br>

namespace Exercises<br>
{<br>
    class GrayCode<br>
    {<br>
        static int getGray(int n)<br>
        {<br>
            return n^(n>>1);<br>
        }<br>
        static void Main(string[] args)<br>
        {<br>
            int InputNum, GrayNum;<br>
            Console.Write("\nEnter the decimal number:");<br>
            InputNum = Convert.ToInt32(Console.ReadLine());<br>
            Console.Write("\n Binary equivalent of {0} : {1}",InputNum,Convert.ToString(InputNum,2));<br>
<br>
            GrayNum = getGray(InputNum);<br>
            Console.Write("\n GrayCode equivalent of {0} : {1}", InputNum, Convert.ToString(GrayNum, 2));<br>
        }<br>
    }<br>
}<br>

OUTPUT:-
![Screenshot (7)](https://user-images.githubusercontent.com/98145032/152290447-4ebf7060-608d-4c56-83c3-c24ce60bfdfd.png)

