// Example program
#include <iostream>
#include <string>
using namespace std;
#include <vector>

int main()
{
  cout << "Welcome to Jackson State University Computer Science Class" << endl;
  
  cout << "These are your students for the course: Mike, Jeremiah, Stan, Jeremy and Eli." << endl;
  
  cout << " Please put their test scores in order of the students" << endl;
  
  vector <int> test_scores {1,2,3,4,5};
  
  cout << "What is Mike's test score?" << endl;
  cin >> test_scores.at(0);
  cout << "Mike test score is " << test_scores.at(0) << endl;
  
   cout << "What is Jeremiah's test score?" << endl;
  cin >> test_scores.at(1);
  cout << "Jeremiah test score is " << test_scores.at(1) << endl;
  
    cout << "What is Stan's test score?" << endl;
  cin >> test_scores.at(2);
  cout << "Stan test score is " << test_scores.at(2) << endl;
  
    cout << "What is Jeremy's test score?" << endl;
  cin >> test_scores.at(3);
  cout << "Jeremy test score is " << test_scores.at(3) << endl;
  
    cout << "What is Eli's test score?"<< endl;
  cin >> test_scores.at(4);
  cout << "Eli test score is " << test_scores.at(4) << endl;
  
  cout << " The class mean is: " << (test_scores.at(0) + test_scores.at(1) + test_scores.at(2) + test_scores.at(3) + test_scores.at(4) ) / 5; 
  
  return 0;
}
