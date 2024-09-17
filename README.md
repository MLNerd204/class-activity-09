#include <iostream>
using namespace std;

int main(){
    
    //insert information:
    
    //Citizen or not:
    bool citizen;
    citizen = true;
    
    //Have a batchlor's degree:
    
    bool Batchlor;
    Batchlor = false;
    
    //years of experience:
    int YearsExp = 6;
    
    //if statment to see if the person is a citizen or not.
    if (citizen == true){
        
        //if true, the program will see if batchlor is true or have at least 2 years of experience.
        if(Batchlor == true or YearsExp >= 2){
            cout<<"You are eligible for the position!"<<endl;
            return 0;
            
        }
        
    }
    //if citizen is not true, batchlor is false, and/or less than 2 years of experience, you are not eligible.
    else;
        cout<<"You are not eligible."<<endl;
    return 0;
}

