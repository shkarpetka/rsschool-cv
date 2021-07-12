### Hanna Ramanava

1. Hanna Ramanava
1. [+375291023901](tel:+375291023901)
1. I want to change my qualification from economist to software engineer. I also worked as an accountant and engineer in the housing and maintenance department.
1. I know HTML/CSS, Photoshop/CorelDraw, Javascript. I used a little jquery.
1. My code examples:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Lab_4</title>
    <!--Напишите функцию decompOfNumb () разложения числовых данных на целое число и дробную часть. -->
    <!--Функция принимает данные, проверяет их «на число» и возвращает массив из 2-х элементов -->
    <!--(целая часть числа и дробная часть) и false, если это совсем не число.-->
    <!--Например:-->
    <!--decompOfNumb(1.25) // функция возвращает [1, 0.25] -->
    <!--decompOfNumb(-30.5) // функция возвращает [-30, 0.5] -->
    <!--decompOfNumb(0.05) // функция возвращает [0,0.05]-->
    <!--decompOfNumb(“не число”) // функция возвращает false-->
  </head>

  <body>
    <script>
      function inputData() {
        const data = prompt("Введите число");
        return Number.parseFloat(data);
      }
      function getResult(number) {
        if (!Number.isFinite(number) || Number.isNaN(number)) {
          return false;
        }
        const der = number.toString().split(".");
        const secondPart = der[1] ? Number("0."+der[1]).toFixed(der[1].length) : "0";
        return [Number(der[0]), secondPart];
      }
      const data = inputData();
      if (!data) {
        document.writeln(data);
      } else {
        document.writeln(getResult(data));
      }
    </script>
  </body>
</html>
```

1. I was building a website from scratch. Design and layout.
1. Engeneer BSUIR, BSU/Software Engeneer (2021-2024) 
1. English level: Beginner
