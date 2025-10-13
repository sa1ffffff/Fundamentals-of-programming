# Fundamentals-of-programming
posting everything i write in my classes &lt;3
//drawing a pyramid
#include <iostream>
using namespace std;
int main()
{
    int n, i, j, spaces;
    cout<<"enter the number of rows u want and press enter: "<<endl;
    cin>>n;
    i=1;
    while(i<=n)
        {    //spaces printing  
            spaces = n-i;    //n-i cz for a 5 line pyramid we need 4 3 2 1 0 spaces
            while(spaces>0)
            {
                cout<<" ";
                spaces--;
            }
            int stars=2*i-1;
            j=1;
            while(j<=stars)      //j needs to run star number of times so as to print odd number of stars for a full pyramid
            {
                cout<<"#";
                j++;
            }
            cout<<endl;
            i++;
        }

        cout<<"Iloveyouuuu emanuuuu";
    return 0;
}
