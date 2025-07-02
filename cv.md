# ***Anastasiya Goncharik***
---
![Logo](https://github.com/Anastasiya247/rsschool-cv/blob/gh-pages/ME.jpg) 
---
## *Contacts*:
* Location: Minsk
* Mob.phone:
    + +37529000000
    + +37533444444
* e-mail: skoraya.10324@gmail.com
* GitHub: Anastasiya247
***
## *About Me*
I work at Alexandrov National Cancer Centre of Belarus as a radiologist.
Also I'm a second-year student of BSUIR.
I'm want to be a Software Engineer. 
***
## *Skills*
* Assembler
* C
* Java
* JS
* Phyton
***
## *Code Example*
```
import java.math.BigInteger;

public class FiboA {

    private long startTime = System.currentTimeMillis();

    private long time() {
        return System.currentTimeMillis() - startTime;
    }

    public static void main(String[] args) {
        FiboA fibo = new FiboA();
        int n = 33;
        System.out.printf("calc(%d)=%d \n\t time=%d \n\n", n, fibo.calc(n), fibo.time());

        fibo = new FiboA();
        n = 33;
        System.out.printf("slowA(%d)=%d \n\t time=%d \n\n", n, fibo.slowA(n), fibo.time());
    }

    private int calc(int n) {
        if (n < 2) return n;
        return calc(n - 1) + calc (n -2);
    }

    BigInteger slowA(Integer n) {
        if (n == 0) return BigInteger.ZERO;
        if (n == 1) return BigInteger.ONE;

        return slowA(n-1).add(slowA(n -2));
    }

 }
```

