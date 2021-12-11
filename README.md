# CMP2241_Task 3 --> Const and & Report
## Usages of **const** keyword:
### Decleration of variables
    ```
    int main()
    {
	    const float pi = 3.14;
    }
    ```
### 
___
## Usages of **&** operator:
### To get the address of the variable.
    ```
    int main ()
    {
        int x;
	    cin >> x;
        cout << &x << endl;
    }
    ```
### To pass by reference.
    ```
    void duplicate(int& n)
    {
	    n *= 2;
    }
    int main()
    {
        int x;
	    cin >>  x;
	    duplicate(x);
	    cout << x;
    }
    ```
### As bitwise operator.
    ```
    int main()
    {
        int a, b;
	    cin >> a >> b;
	    int s = a & b;
	    cout << s << endl;
    ]
    ```
