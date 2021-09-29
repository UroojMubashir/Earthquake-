#include <iostream>
#include <string>
using namespace std;
int main()
{
    int magnitude;
    cout << "Enter the Magnitude Value :";
    cin >> magnitude;
    
    if (magnitude < 2.0)
    {
        cout << "Earthquak is consider to be Micro Earthquake" ;
    }

    else if (magnitude <= 2.0 && magnitude < 3.0)
    {
       cout << "Earthquak is consider to be Very Minor Earthquake " ;
    }

    else if (magnitude <= 3.0 && magnitude < 4.0)
    {
        cout << "Earthquak is consider to be  Minor Earthquake " ;
    }
    else if (magnitude <= 4.0 && magnitude < 5.0)
    {
        cout << "Earthquak is consider to be Light Earthquake " ;
    }
    else if (magnitude <= 5.0 && magnitude < 6.0)
    {
        cout << "Earthquak is consider to be Moderate Earthquake " ;
    }
    else if (magnitude <= 6.0 && magnitude < 7.0)
    {
        cout << "Earthquak is consider to be Strong Earthquake " ;
    }
    else if (magnitude <= 7.0 && magnitude < 8.0)
    {
        cout << "Earthquak is consider to be Major Earthquake " ;
    }
    else if (magnitude <= 8.0 && magnitude < 10.0)
    {
        cout << "Earthquak is consider to be Great Earthquake "  ;
    }

    else if (magnitude >= 10)
    {
        cout << "Earthquak is consider to be Meteoric Earthquake " ;
    }

    else
    {
        cout << "Not a valid input.";
    }
}
