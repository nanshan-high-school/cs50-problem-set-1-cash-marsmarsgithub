#include <iostream>
 
using namespace std;
int main() {
   int money;
   cout << "請輸入金錢數";
  cin >> money;
   cout << money/50 << "個五十元數。\n"
        << money%50/10 << "個十元數。\n"
        << money%50%10/5 << "個五元數。\n"
        << money%50%10%5/1 << "個一元數。\n總共"
        << money/50+money%50/10+money%50%10/5  +money%50%10%5/1 <<"硬幣數。\n";


 
}
