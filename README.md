# ortalama
package day01;

import java.util.Scanner;

public class day1 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int fizik,matematik,turkce,kimya,muzik,tarih;

        System.out.print("Fizik Notunuz= ");
        fizik=input.nextInt();

        System.out.print("Matemetik Notunuz= ");
        matematik=input.nextInt();

        System.out.print("Türkçe Notunuz= ");
        turkce=input.nextInt();

        System.out.print("Kimya Notunuz= ");
        kimya=input.nextInt();

        System.out.print("Müzik Notunuz= ");
        muzik=input.nextInt();

        System.out.print("Tarih Notunuuz= ");
        tarih=input.nextInt();


        double sonuc = (fizik + matematik + turkce + kimya + muzik + tarih) / 6;
        System.out.println("Ortalamanız= " + sonuc);
