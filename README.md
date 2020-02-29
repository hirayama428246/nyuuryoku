# nyuuryoku
//インポートを使用した入力受付　
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        System.out.println("占い館へようこそ");

        System.out.println("年齢を入力してください");

        //Scanner age = new Scanner(System.in);
        //String agenyuuryoku = age.next();
        String age = new Scanner(System.in).nextLine();
 
        System.out.println("あなたの名前を教えてください");
        
 
        //Scanner name = new Scanner(System.in);
        //String namenyuuryoku = name.next();
        String name = new Scanner(System.in).nextLine();
        
        int fortune = new java.util.Random().nextInt(4)+1;//乱数作成
 
        System.out.println("占いの結果が出ました");
 
        System.out.println(age+"歳の"+name+"さんあなたの運気番号は"+fortune+"です");
 
        System.out.println("1:大吉2:中吉3:吉4:凶");
    }
}
