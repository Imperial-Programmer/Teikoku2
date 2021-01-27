#include <iostream>
using namespace std;

int main()
{
  const int arraySize = 5;
  double Number;
  int array[arraySize] = {32, 431, -34, 23, 12};
  int flag;


  flag = 0;

  cout << "Mau angka berapa? : ";
  cin >> Number;

  for(int cntr = 0; cntr < arraySize; cntr++)
  {
    if(array[cntr] == Number)
    {
cout << "Wah ada! " << cntr << "."
     << endl;

      flag += 1;
    }
  }
  

  if(flag < 1)
  {
    cout << "KAGA ADA!" << endl;
  }

  cin.get();
  return 0;
}
