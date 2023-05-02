1. Какво ще се изпише в етикета message след изпълнение на програмния фрагмент?

```
float i = 15;
do --i;
while (i > -7);
lblResult.setText(i.toString());
```

- -6
- -7
- -8
- 14



2. Kакво ще изведе даденият по-долу фрагмент?

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

- two
- three
- another
- никое от изброените


3. Kакво ще изведе даденият по-долу фрагмент?
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

- 0
- 4
- RuntimeException
- 