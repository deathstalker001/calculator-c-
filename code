#include <iostream>

using namespace std;

int main()
{
    int a;
    int b;
    int ask;
    int result;
    bool first_question_correct = true;
    bool run;
    bool ask_run_correct = true;
    int ask_run;


do
{
    do {
        cout << "Type:\n" << "-'1' to calculate a sum between two numbers\n";
        cout << "-'2' to calculate the difference between two numbers\n";
        cout << "-'3' to make the division between two numbers\n";
        cout << "-'4' to make the product between two numbers\n";
        cout << "-'5' to get remainder of dividing two numbers\n";
        cin >> ask;

        if (ask == 1 || ask == 2 || ask == 3 || ask == 3 || ask == 4 || ask == 5) {
            cout << "Alright! So now tell me the first number you want to operate with!\n";
            cin >> a;
            cout << "Now tell me the second number you want to operate with...\n";
            cin >> b;

            if (ask == 1){
                result = a+b;
                cout << "The sum between " << a << " and " << b << " is: " << result << "\n";
            }
            else if (ask == 2){
                result = a-b;
                cout << "The diference between " << a << " and " << b << " is: " << result << "\n";
            }
            else if (ask == 3){
                result = a/b;
                cout << "The division between " << a << " and " << b << " is: " << result << "\n";
            }
            else if (ask == 4){
                result = a*b;
                cout << "The product between " << a << " and " << b << " is: " << result << "\n";
            }
            else if (ask == 5){
                result = a%b;
                cout << "The remainder of dividing " << a << " and " << b << " is: " << result << "\n";
            }

        }
        else {
            cout << "You didn't entered the right number!\nPlease try again...";
            first_question_correct = false;
        }

        do {
            cout << "Do you want to make another operation?\nType:\n-'1' To continue\n-'2' to stop\n";
            cin >> ask_run;

        if (ask_run == 1) {
            run = true;
        }
        else if (ask_run == 2) {
            run = false;
        }
        else {
            ask_run_correct = false;
        }

    } while (!ask_run_correct);

    } while (!first_question_correct);

} while (run);
    return 0;
}
