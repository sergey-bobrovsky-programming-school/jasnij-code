speed = 20 - var speed = 20 // JS: явное объявление переменной

var speed = 20 - const speed = 20 // JS: предпочтительно объявлять переменные как const

int studentsCount = 20;
int speed = 5;
int time = 10;
int distance = speed * time;

// studentsCount - неиспользуемая переменная, которую следует удалить

public class Car {
    public String color;
    public int doorsCount;

    public Car(String _color) {
        color = _color;
    }

    public void ride(int _doorsCount) {
        doorsCount = _doorsCount;
    }
}

// свойство doorsCount должно быть проинициализировано в конструкторе


int i = null

for(i=0; i<str1.length(); i++) - for(int i=0; i<str1.length(); i++) // инициализация счетчика цикла должна находиться в заголовке самого цикла

public square(int number) {
    if (number < 0) {
        throw Error // инвариант проверяющий корректность входного значения функции
    }
}

int sum = 0

for(i=0; i<str1.length(); i++) - for(int i=0; i<str1.length(); i++) {
    sum = sum + i;
}

for(i=0; i<str2.length(); i++) - for(int i=0; i<str1.length(); i++) {
    sum = sum + i;
}

// один аккумулятор используется в двух циклах что может приводить к ошибкам. Для каждого цикла нужно иметь свой аккумулятор.

