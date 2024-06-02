public class Main {
    public static void main(String[] args) {

        int status = 100;
        int adding = 1100;
        int bonus = 0;
        int x = 1;
        if (adding > 1000) {
            bonus = adding / 100;
        }

        int overall = status + adding + bonus;
        System.out.println("Баланс был " + status);
        System.out.println("Пополнение на " + adding);
        System.out.println("Бонусы " + bonus);
        System.out.println("Итоговый баланс " + overall);

    }
}