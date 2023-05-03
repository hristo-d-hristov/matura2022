# Пробна матура по информатика, 3 май 2023

<style>
  .markdown-body .highlight pre, .markdown-body pre, .markdown-body .highlight {
    background-color: transparent;
  }
  .footer {
    display: none;
  }
</style>

(1). Какво ще се изпише в етикета message след изпълнение на програмния фрагмент?

```
float i = 15;
do --i;
while (i > -7);
message.setText(i.toString());
```

а) -6 <br>
б) -7 <br>
в) -8 <br>
г) 14 <br>

---

(2). Kакво ще изведе даденият по-долу фрагмент?

```
switch (2) {
  case 1:
    System.out.println("one");
  case 2:
    System.out.println("two");
  case 3:
    System.out.println("three");
  default:
    System.out.println("another");
}
```

а) two <br>
б) three <br>
в) another <br>
г) никое от изброените <br>

---

(3). Kакво ще изведе даденият по-долу фрагмент?

```
public class Shadow {
    static int a;
    public static void main(String[] args) {
        int a;
        a = 4;
        System.out.println(Shadow.a);
    }
}
```

а) 0 <br>
б) 4 <br>
в) RuntimeException <br>
г) друго <br>

---

(4). Христо

---

(5). Христо

---

(6). Христо

---

(7). Христо

---

(8). Христо

---

// от тук са моите въпроси от 9 до 20

(9). Кое твърдение е вярно:

а) Функцията (методът) в Java има точно един оператор return;<br>
б) Функцията (методът) в Java има поне един оператор return;<br>
в) Функцията (методът) в Java връща най-много една стойност;<br>
г) Функцията (методът) в Java не връща стойност;<br>

---

(10). Кои са първите две операции, които ще се изпълнят при пресмятане стойността на израза?
```
A = 11.45 / 5 - 3.5 * ( 12.7 + 4.5 );
```
а) деление и събиране <br>
б) деление и умножение <br>
в) деление и действието в скобите <br>
г) умножение и действието в скобите <br>

---

(11). Три променливи са инициализирани по следния начин:
```
String a2="cat", a1="dog", a3="category";
```
Кой от следните изрази има стойност истина? <br>
а) a1.compareTo(a2) < 0 <br> 
б) a2.compareTo(a3) < 0 <br> 
в) a3.compareTo(a1) > 0 <br> 
г) a1.compareTo(a2) <=0 <br> 

---

(12). Кое твърдение не е вярно?

<img src="pic_3.jpg" width="30%"/>

а) private_client е с дефиниция <b>protected </b> <br>
б) методът number е с дефинициия <b>public </b> <br>
в) number може да бъде наследяван <br>
г) dispatch може да бъде пренаписван (overload) от наследниците <br>

---

(13). Каква ще бъде стойността на променливата day след изпълнение на програмния фрагмент?
```
String [] array = {"понеделник", "вторник", "сряда", "четвъртък", "петък"};
String day = "понеделник";
for(int i=1; i < array.length; i++){
if(array[i] == "събота")
day = "неделя";
}
```
а) петък <br>
б) понеделник <br>
в) събота <br>
г) неделя <br>

---

(14). Запишете стойността, която ще бъде изписана на екрана след обръщението Func(21) ?
```
public static void Func (inr n) {
if (n<=0) {
  return ;
  }
Func (n/3);
System.out.print(n%3);
}
```

а) 202 <br>
б) 012 <br>
в) 210 <br>
г) 201 <br>

---

(15). В кой от програмните фрагменти тялото на цикъла ще се изпълни един път?

<table>
  <tbody>
    <tr> <b>
      <td> а)</td>
      <td> б) </td>
      <td> в) </td>
      <td> г) </td>
      </b> </tr>
    <tr>
      <td>int sum = 0; <br>
        int i = 1; <br>
        do { <br>
        sum + = i; <br>
        i++; <br>
        } while (i <= 3);
        </td>
      <td> int sum=0; <br>
      for (int i=1; i<=2; i+=2) <br>
             sum+=i;
      </td>
      <td>int sum = 0; <br>
        int i = 1; <br>
        while (i>=2){ <br>
        sum+=i; <br>
        i++; <br>
        }  <br>      
      </td>
      <td>int sum = 0; <br>
        int i = 1; <br>
        while (i<=2) { <br>
        sum+=i; <br>
        i++; <br>
        } <br>
      </td>
    </tr>
  </tbody>
</table>

---

(16). Кой от следните методи е <b>set</b> свойство на поле данни, декларирано като
```
private String lastName ;
```
a) private String setLastName (String name) { name = lastName; } <br>
б) private String setLastName (String name) { return name; } <br>
в) public void setLastName() { return lastName; }  <br>
г) public void setLastName (String name) { lastName=name; } <br>

---

(17). Подреди операторите в правилна последователност, така че след програмния фрагмент да получиш стойност beta=9.
Непосредствено преди тези редове са използвани декларациите:
```
int alpha=12/4;
int beta=Math.floor(-3.6);
int gamma=(12/5)++;
```
а)  else beta++; <br>
б)  else beta=Math.pow(beta, 2); <br>
в)  if (alpha>=beta) alpha++; <br>
г)  if (beta>=gamma) beta=Math.pow(gamma, 2); <br>
   

---

(18). При стартиране е въведена стойност за а=3. Допиши условието от последния ред, така че маркираният със стрелка оператор да се изпълни точно 9 пъти? <br>

<img src="pic_1.jpg" width="500"/>

---

(19). Попълни стойностите на елементите след изпълнение на програмния фрагмент.
```
string [] things={"pen", "pergel", "notebook", "tape"};
for (int i=1; i < 4; i++)
     things[i]=things[i-1]+"s";
```
things[0]= &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;; <br>
things[1]= &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;; <br>
things[2]= &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;; <br>

---

(20). Какво стойности на <b>S</b> и на <b>Index</b> ще бъдат отпечатани след изпълнение на програмния код: <br>

<img src="pic_2.jpg" width="600"/>

---

(21). Христо

---

(22). Христо

---

(23). Христо

---

(24). Христо


[> Втора част](vtora-chast.html)
