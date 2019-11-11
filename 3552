#include <iostream>
#include <cmath>
using namespace std;

bool isInTriangle (double x, double y)
{
    if(x>=2 && y>=2 && x<=7 && y<=7 && y<=-x+6)
    {
        return true;
    }
    return false;
}

double pokeball (double x, double y, double x1, double y1)
{
    return sqrt((x-x1)*(x-x1) + (y-y1)*(y-y1));
}

bool isInPokeball (double x, double y)
{
    if (y>=0 && (pokeball(x, y, -9, 0)<=3) && (pokeball(x, y, -9, 0)>=1))
    {
        return true;
    }
    return false;
}

int main()
{
    double n;
    double x, y;
    cout<<"n=";
    cin>>n;
    for (int i=0; i<n; i++)
    {
        cout<<"Enter x, y: ";
        cin>>x>>y;
        if (isInPokeball(x,y)==true)
        {
            cout<<"Inside the Pokeball"<<endl;
}
        else if (isInTriangle(x,y)==true)
        {
            cout<<"Inside the Triangle"<<endl;
        }
        else
        {
            cout<<"Outside the coloured areas"<<endl;
        }
    }
    return 0;
}
