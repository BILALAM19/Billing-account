#include <iostream>
using namespace std;

int main()
{
    int prodprice1;
    int numprod1;
    int Taxreason = 32;

    cout << "Single product 1 : ";
    cin >> prodprice1;

    cout << "Number of products purchased : ";
    cin >> numprod1;

    int totalprice = prodprice1 * numprod1;

    cout << "Total price : " << totalprice << endl;

    double Tax = totalprice * (Taxreason / 100.0);
    cout << "Tax : " << Tax << " dz." << endl;

    double finalbill = totalprice + Tax;
    cout << "Final bill : " << finalbill << " dz." << endl;
}
