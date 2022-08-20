# NotOrtalamas-HesaplayanProgram
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
      // değişkenleri not al
      int mat,fizik,kimya,turkce,tarih,muzik;

        // scanner snıf oluştur

        Scanner inp = new Scanner(System.in);
        // kullanıcıdan değer al
        System.out.print("Matematik Notunuzu : ");
        mat = inp.nextInt();
        System.out.println(mat);

        System.out.print("Fizik Notunuz : ");
        fizik = inp.nextInt();
        System.out.println(fizik);

        System.out.print("Kimya Notunuz : ");
        kimya = inp.nextInt();
        System.out.println(kimya);

        System.out.print("Türkçe Notunuz : ");
        turkce = inp.nextInt();
        System.out.println("turkce");

        System.out.print("Tarih Notunuz : ");
        tarih = inp.nextInt();
        System.out.println("tarih");

        System.out.print("Müzik Notunuz : ");
        muzik = inp.nextInt();
        System.out.println("muzik");

        double ortalama = (mat+fizik+kimya+turkce+tarih+muzik)/6;
        System.out.println("Ortalama:"+ortalama);
        String sonuc = ortalama  >=50  ? "Geçtiniz" : "kaldınız";
        System.out.println(sonuc);
        System.out.println(ortalama);
