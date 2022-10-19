# loopgame
#include <iostream>
#include <cstdlib>
#include <ctime>
#include <string>
using namespace std;

int main()
{
  srand(static_cast<unsigned int>(time(0)));
  int serectNumber;
  int gateNumber=6;
  string Enter;
cout << "あなたは最終関門の扉のまえにいます。サイコロを降って６がでたら扉はひらきます。それではサイコロを振ってください。";
  do{cout << "サイコロを振るには";
  do{
     cout << "Fをおしてください。";
  cin>> Enter;
   }while(
  Enter!="F");
   serectNumber=rand()%6+1; 
  cout << serectNumber << endl;
    if(serectNumber!=gateNumber){
  cout << "扉は開きませんでした。";}
    }while(
serectNumber!=gateNumber);
cout << "扉は開きました。あなたの勝利です。";
  }
