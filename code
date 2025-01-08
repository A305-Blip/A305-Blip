Write a program in C++ to implement stack using array, push 6 values in the stack and display them.
#include <iostream>
using namespace std;
// Define the maximum size of the stack
const int MAX_SIZE = 6;
class Stack {
private:
    int arr[MAX_SIZE]; // Array to store stack elements
    int top; // Index of the top element
public:
    // Constructor to initialize stack
    Stack() {
        top = -1; // Indicates the stack is empty
    }
 // Push function to add an element to the stack
    void push(int value) {
        if (top == MAX_SIZE - 1) {
            cout << "Stack overflow! Cannot push more elements." << endl;
        } else {
            arr[++top] = value; // Increment top and insert the value
        }
    }
 // Function to display all elements in the stack
    void display() {
        if (top == -1) {
            cout << "Stack is empty!" << endl;
        } else {
            for (int i = top; i >= 0; i--) {
                cout << arr[i] << " ";
            }
            cout << endl;
        }
    }
};
int main() {
    // Create a stack object
    Stack myStack;
// Read 6 values from the user and push them into the stack
    // cout << "Enter 6 values to push into the stack: " << endl;
    for (int i = 0; i < MAX_SIZE; i++) {
        int value;
        cin >> value;
        myStack.push(value);
    }
 // Display the stack elements
    cout << " ";
    myStack.display();
 return 0;
}
