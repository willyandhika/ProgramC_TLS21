# ProgramC_TLS21
Willybrodus Andhika B / Radix
#include <iostream>
using namespace std;

int main()
{
    int array[50], i, n;
    float avg, total=0;
    
    cout << "Total and Average of Mid-Term Test" << endl;
    cout << "==================================" << endl;
    cout << "Total Subjects : ";
    cin >> n;
    
    for(i=0; i<n; i++)
    {
        cout << "Score " << i+1 << " : ";
        cin >> array[i];
        total = total + array[i];
    }
    
    avg = total/n;
    cout << "==================================" << endl;
    cout << "Total : " << total << endl;
    cout << "Average : " << avg << endl;
  
    return 0;
}
