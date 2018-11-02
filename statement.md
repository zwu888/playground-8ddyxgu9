# 

```C++ runnable
#include<iostream>
using namespace std;
class Person {
    public:
        Person(const char* stName)
        {}
        const char* GetName() const
        {}
        // this is needed for cout << person
        operator const char*() const { return "John";}
    private:
        char* m_stName;
};
int main()
{
    Person person("John");
    cout << person << endl;
    
    foo();
    return 0;
}
```

