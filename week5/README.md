# **Цикли и функции**
<br />
<br />


#### **Функции**
```cpp
#include <iostream> 
using namespace std;

void print_args(int arg1, float arg2, char arg3)
{
    cout<<"arg1: " << arg1 << ", arg2:" << arg2 << ", arg3:" << arg3 << endl
}

int max(int arg1, int arg2)
{
    if(arg1>arg2)
    {
        return arg1;
    }
    else
    {
        return arg2;
    }
}

int main() {
    print_args(1, 2.2, 'a');// prints "arg1: 1, arg2:2.2, arg3:a"
    cout<<max(1,2)<<endl; // prints "2"
    return 0;
}
```

<br />

# **Задачи**

## **Направете функция, която:**
<br />
<br />

### **Задача 1:**
    връща n-тото число на фибоначи
<br />   

### **Задача 2:**
    принитира в обратен ред число, което е подадено като аргумент 
<br />

### **Задача 3:**
    повдига дадено число на степен
<br />

### **Задача 4:**
    връща факториел от дадено число
<br />

### **Задача 5:**
    при подадени аргументи n и х връща сумата 1+x+x^2/2!+x^3/3!+.... до n
<br />

### **Задача 6:**
    проверява дали едно число е просто
<br />

### **Задача 7:**
    проверява дали едно число може да се представи като сбор от 2 прости числа
<br />

### **Задача 8:**
    при подаден аргумент num (цяло число), връща най-голямото двуцифрено число, образувано от две поредни цифри в num
<br />

### **Задача 9:**
    проверява дали всяка цифра в число, подадено като аргумен, е по-голяма от предходната
    
    