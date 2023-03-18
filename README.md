public class JvmComprehension {

    public static void main(String[] args) {
        int i = 1;                      // Создаём примитивниый числовой тип переменной i со значением 1
        Object o = new Object();        //  Создаём объект о
        Integer ii = 2;                 //  Создаём числовой ссылочный тип данных со значением 2
        printAll(o, i, ii);             // вызываем метод
        System.out.println("finished"); // пишем в консоль "finished"
    }

    private static void printAll(Object o, int i, Integer ii) {
        Integer uselessVar = 700;                   // Создаём числовой ссылочный тип данных со значением 700
        System.out.println(o.toString() + i + ii);  // Выводим в консоль метод класса Object, переменные i, ii
    }
}