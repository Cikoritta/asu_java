В Java типы данных можно разделить на примитивные и ссылочные. Примитивные типы данных представляют собой простые значения, такие как числа и символы. Ссылочные типы данных включают объекты и массивы.

Java имеет 8 примитивных типов данных:


1. **byte**: 8-битное целое число
   ```java
   byte b = 100;
   ```

2. **short**: 16-битное целое число
   ```java
   short s = 10000;
   ```

3. **int**: 32-битное целое число
   ```java
   int i = 100000;
   ```

4. **long**: 64-битное целое число
   ```java
   long l = 10000000000L;
   ```

5. **float**: 32-битное число с плавающей запятой
   ```java
   float f = 10.5f;
   ```

6. **double**: 64-битное число с плавающей запятой
   ```java
   double d = 20.99;
   ```

7. **char**: 16-битный символ Unicode
   ```java
   char c = 'A';
   ```

8. **boolean**: Логический тип (true или false)
   ```java
   boolean bool = true;
   ```

## Ссылочные Типы Данных

Ссылочные типы данных включают объекты и массивы. Примеры:

1. **String**: Класс для работы со строками
   ```java
   String str = "Hello, World!";
   ```

2. **Массивы**: Контейнеры для хранения нескольких элементов одного типа
   ```java
   int[] numbers = {1, 2, 3, 4, 5};
   ```

## Объявление Переменных

Для объявления переменных указывайте тип данных и имя переменной:

```java
int age;
String name;
```

Инициализация переменной происходит при присвоении значения:

```java
age = 30;
name = "Alice";
```

Можно объединить объявление и инициализацию:

```java
int age = 30;
String name = "Alice";
```

## Ввод Данных

Для ввода данных в Java можно использовать класс `Scanner`. Пример:

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Введите ваше имя: ");
        String name = scanner.nextLine();

        System.out.print("Введите ваш возраст: ");
        int age = scanner.nextInt();

        System.out.println("Привет, " + name + "! Вам " + age + " лет.");
    }
}
```

## Вывод Данных

Для вывода данных в Java можно использовать `System.out.println()` и `System.out.print()`. Примеры:

```java
// Вывод с переводом строки
System.out.println("Привет, мир!");

// Вывод без перевода строки
System.out.print("Привет, ");
System.out.print("мир!");
```
