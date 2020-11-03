#include <iostream>
using namespace std;
 
int main() {
    int i, count, sum, inputArray[500];
    float average;
    
    cout << "Enter number :";
    cin >> count
    for(i = 0; i < 21; i++) {
        cin >> inputArray[i];
    }
    sum = 0;

    for(i = 0; i < count; i++) {
        sum += inputArray[i];
    }
 
    average = (float)sum / count;
    cout << "Average = " << average;
 
    return 0;
}
