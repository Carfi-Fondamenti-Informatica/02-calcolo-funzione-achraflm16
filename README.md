# 02-calcolo-funzione-achraflm16
02-calcolo-funzione-achraflm16 created by GitHub Classroom
#include <iostream>
using namespace std;
int main() {
    float a=0, b=0, x=0, y=0, z=0;

    cin >> a >> b >> x >> y;

    if(x < 0 && y > 0){
        z = a*x - b*y;
    }else if(x >= 0 && y <= 0){
        z = a*x*x - b*y;
    }else{
        z = a*x + b*y*y;
    }

    cout << z;
    return 0;
}
