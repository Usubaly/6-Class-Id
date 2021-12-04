# 6-Class-Id
6.1. Понятие Class и Id - атрибуты
<!DOCTYPE html>
<html>
    <head>
        <title>4-sabak</title>
        <style>
            .li3 {color: red;}
            #li4 {color: rgb(0, 22, 186);}
        </style>
    </head>
    <body>
        <!-- 4-сабак Тизмелер жана Таблицалар менен машыгабыз-->

        <!-- маркированный список -->
        
        <ul type='square'>
            <li class="li3">Маркирленген элементтин тизмеси</li>
            <li>Март</li>
            <li class="li3">Апрель</li>
            <li>Май</li>            
        </ul>
          
         <!-- номерленген тизме -->
        <ol>
            <li>Номерленген тизме</li>
            <li>Бир</li>
            <li>Эки</li>
            <li>Үч</li> 
        </ol>
        <P></P>
        <P></P>
        <P></P>
        

         <!-- Таблица -->

        <table align="center">                              
            <tr>
                <td>Бир</td>
                <td class="li3">Эки</td>
                <td>Үч</td>
                <td class="li3">Төрт</td>
            </tr>
            <tr>
                <td>Бир</td>
                <td class="li3">Эки</td>
                <td>Үч</td>
                <td class="li3">Төрт</td>
            </tr>
            <tr>
                <td class="li3">Бир</td>
                <td id="li4">Эки</td>
                <td class="li3">Үч</td>
                <td>Төрт</td>
            </tr>
        </table>
        
        <!-- 5-урок Практика работы с Формами -->

        <form action="" method="POST"> 

            <input type="text" name="as_q">
            <input type="submit">

            


        </form>


        <!-- 6-сабак Понятие Class и Id - атрибуты -->

        <ol>
            <li>Номерленген тизме</li>
            <li class="li3">Бир</li>
            <li>Эки</li>
            <li id="li4">Үч</li> 
        </ol>

    </body> 



</html>
