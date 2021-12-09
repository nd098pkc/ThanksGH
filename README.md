<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="java.css" rel="stylesheet">
</head>
<body>
    <nav class="table">
        <div class="result"></div>
        <div class="buttons">
            <ul>
                <li class="line1">
                    <ul>
                        <li id="percentage" onclick="Percent()">%</li>
                        <li id="reset" onclick="Reset()">CE</li>
                        <li id="clear">C</li>
                        <li id="backspace">←</li>
                    </ul>
                </li>
                <li class="line2">
                    <ul>
                        <li id="reverse">1/x</li>
                        <li onclick="square()">x²</li>
                        <li id="root">√</li>
                        <li id="divide">/</li>
                    </ul>
                </li>
                <li class="line3">
                    <ul>
                        <li id="seven" onclick="num7()">7</li>
                        <li id="eight" onclick="num8()">8</li>
                        <li id="nine" onclick="num9()">9</li>
                        <li id="muti">X</li>
                    </ul>
                </li>
                <li class="line4">
                    <ul>
                        <li id="four" onclick="num4()">4</li>
                        <li id="five" onclick="num5()">5</li>
                        <li id="six" onclick="num6()">6</li>
                        <li id="minus">-</li>
                    </ul>
                </li>
                <li>
                    <ul>
                        <li id="one" onclick="num1()">1</li>
                        <li id="two"onclick="num2()">2</li>
                        <li id="three"onclick="num3()">3</li>
                        <li id="plus" onclick="Plus()">+</li>
                    </ul>
                </li>
                <li>
                    <ul>
                        <li onclick="num0()">0</li>
                        <li></li>
                        <li></li>
                        <li id="equal" onclick="goEqual()">=</li>
                    </ul>
                </li>
            </ul>

        </div>
    </nav>
</body>
</html>

