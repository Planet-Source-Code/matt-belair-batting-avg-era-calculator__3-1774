<div align="center">

## Batting Avg/ERA calculator


</div>

### Description

Simple DOS calculator that calculates batting averages and earned run avg for baseball players
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Matt Belair](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/matt-belair.md)
**Level**          |Beginner
**User Rating**    |3.0 (6 globes from 2 users)
**Compatibility**  |C\+\+ \(general\)
**Category**       |[Math](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math__3-12.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/matt-belair-batting-avg-era-calculator__3-1774/archive/master.zip)





### Source Code

```
#include <iostream.h>
float x, y;
int main ()
{
bool done = false;
int x,y,z;
int a,b,c,d;
for(;;)
{
cout << "\nWelcome To Batting Avg Calculator By Matt Belair!\n";
cout<<"Version 1.0 Compiled May 17. 2k1 AD\n";
cout << "\nMain Menu- Choose an option\n";
    cout << "[1] Calculate Your Batting Avg.\n";
cout << "[2] Calculate Pitchers Era\n";
cout << "[3] Quit\n";
    cin >> z;
    switch (z)
      {
case 1:
cout << "\nEnter Number of Hits:\t";
    cin >> x;
    cout << "Enter Number of At Bats:\t";
    cin >> y;
 cout <<"Batting avg:\t\t"<<(float)x/y<<endl;
	break;
case 2:
cout << "\nEnter The Number of Earned Runs given up:\t";
cin>>a;
cout << "\nEnter number of Innings Pitched:\t";
cin>>b;
cout << "\nEnter number of innings in a standard game:\t";
cin >>c;
cout <<"ERA:\t\t"<<(float)a/b*c<<endl;
      break;
case 3:
      done = true;
      break;
      default:
      cout << "Make another Selection";
      break;
}
if (done)
break;
}
return 0;
}
```

