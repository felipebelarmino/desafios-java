```
// desafio 1
import java.util.Scanner;
public class Programa {
    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        int n;
        n = ler.nextInt();

        for (int i = 1 ; i <=n; i++) {
            if (i % 2 == 0 ) System.out.println(i);
        }
    }
}

// desafio 2
import java.util.Scanner;
public class Idade {
    public static void main(String[] args) {
        Scanner leitor = new Scanner(System.in);
        int idadeDias = leitor.nextInt();
        int anos =  idadeDias / 365;
        int meses =  (idadeDias - (anos * 365)) / 30;
        int dias = idadeDias - ( (meses * 30)+ (anos * 365));
        System.out.println( anos + " ano(s)");
        System.out.println( meses + " mes(es)");
        System.out.println( dias + " dia(s)");
    }
}

// desafio 3
import java.util.Scanner;
public class Idade {
    public static void main(String[] args) {
        Scanner leitor = new Scanner(System.in);
        int nota = leitor.nextInt();
        if (nota == 0) {
            System.out.println("E");
        } else if (nota <= 35) {
            System.out.println("D");
        } else if (nota <= 60) {
            System.out.println("C");
        } else if (nota <= 85) {
            System.out.println("B");
        } else {
            System.out.println("A");
        }
    }
}
```
