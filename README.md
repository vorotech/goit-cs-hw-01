## goit-cs-hw-01

### Завдання 1

Компіляція

```sh
cd task_1
nasm -f bin -o calc.com calc.asm
mkdir -p D:\\asm
cp calc.com D:\\asm\\
```

DOSBox

```sh
Z:\> mount c d:\\asm
Z:\> C:
C:\> CALC.COM
Result: 6
```

![](./task_1/dosbox.png)

### Завдання 2

Тестування

```
Введіть вираз (або "exit" для виходу): (2 + 3) * 4
20
Введіть вираз (або "exit" для виходу): (2 + 3) * (2 + 3)
25
Введіть вираз (або "exit" для виходу): (2 + 3) * (2 + 6)
40
Введіть вираз (або "exit" для виходу): exit
Вихід із програми.
```