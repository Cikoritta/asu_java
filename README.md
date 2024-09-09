<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Гайд по типам данных в Java</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1, h2 {
            color: #333;
        }
        code {
            background: #f4f4f4;
            border: 1px solid #ddd;
            border-radius: 4px;
            padding: 0.2em 0.4em;
        }
        pre {
            background: #f4f4f4;
            border: 1px solid #ddd;
            border-radius: 4px;
            padding: 10px;
            overflow-x: auto;
        }
    </style>
</head>
<body>
    <h1>Гайд по типам данных, их объявлению, вводу и выводу в Java</h1>

    <h2>Типы данных в Java</h2>
    <p>Java поддерживает два основных типа данных:</p>
    <ul>
        <li><strong>Примитивные типы данных:</strong> byte, short, int, long, float, double, char, boolean</li>
        <li><strong>Ссылочные типы данных:</strong> классы, интерфейсы, массивы</li>
    </ul>

    <h3>Примитивные типы данных</h3>
    <p>Примитивные типы данных имеют фиксированный размер и представляют базовые значения.</p>
    <pre><code>// Примеры объявления примитивных типов данных
int myNumber = 42;
double myDouble = 3.14;
char myChar = 'A';
boolean myBoolean = true;
    </code></pre>

    <h2>Объявление переменных</h2>
    <p>Переменные в Java объявляются с указанием типа данных, после чего следует имя переменной и её начальное значение (необязательно).</p>
    <pre><code>// Пример объявления переменной
int age = 25;
String name = "Иван";
    </code></pre>

    <h2>Ввод данных</h2>
    <p>Для ввода данных из консоли используется класс <code>Scanner</code>.</p>
    <pre><code>import java.util.Scanner;

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
    </code></pre>

    <h2>Вывод данных</h2>
    <p>Для вывода данных используется класс <code>System.out</code>. В основном применяются методы <code>print</code>, <code>println</code> и <code>printf</code>.</p>
    <pre><code>System.out.println("Привет, мир!"); // Печатает строку и переходит на новую строку
System.out.print("Привет, мир!"); // Печатает строку без перехода на новую строку
System.out.printf("Возраст: %d лет\n", age); // Печатает отформатированную строку
    </code></pre>

</body>
</html>
