
 
<!---1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
#include "pch.h"
#include <iostream>
 
int main()
{
    using namespace std;
 
    int probel2 = 0;
    int startSymbols = 11;
    char symbol = 'a';
    for (int s = 0; s <= 2; s++)  //кол-во строк букв
    {
        for (int z = 1; z < 3; z++)  //кол-во пробелов  
            cout << " ";
        for (int t = 0; t<=2; t++)  // количество букв в строке 
            cout << symbol;
        if (s == 2) break;
    }
        for (int i = probel2; i >= 0; i++)  // цикл будет выполняться пока не закончатся буквы 
        {
            for (int k = 0; k < i; k++)  // в этом цикле мы ресуем пробелы в начале строки 
                cout << " ";
            for (int j = 0; j < startSymbols; j++) // рисуем символ столько раз сколько записываем переменную 
                cout << symbol;
            startSymbols -= 2; // каждую новую строчку отнимаем 2 символа 
            cout << endl; 
            if (probel2 == 10) ; // когда закончились буквы в строке, то заверщаем цикл
            
        }
        
}
 
danirel/danirel is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
