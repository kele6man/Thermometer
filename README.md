# Thermometer
<h2> Кода управлява 7 сегментен дисплей с 4 цифри, като измерва температурата с DHT11 сензор и я показва на дисплея.</h2>

Този код показва текущата температура на 7-сегментен дисплей, свързан към дъска Raspberry Pi Pico. Датчик DHT11 измерва температурата и изпраща данни до Pico борда, който след това актуализира дисплея.

<h3>Предварителни изисквания:</h3>
<ul>
  <li>Платка Raspberry Pi Pico</li>
  <li>7-сегментен дисплей модул с 4 цифри</li>
  <li>Модул DHT11 сензор</li>
  <li>Скоби или кабели за свързване на сензори и дисплей към Pico дъската</li>
</ul>

<h3>Инструкции:<h3/>
Свържете сензора DHT11 и 7-сегментния дисплей към Pico според пиновата диаграма:
<picture>
  <img alt="Пинова диаграма" src="https://ibb.co/DrKy1rP">
</picture>

<h3>Свалете кода като използвате следната команда:</h3>
```git clone https://github.com/kele6man/Thermometer.git```

Температурата ще бъде показана на 7-сегментния дисплей в градуси по Целзий. Цифрите се актуализират на всеки 500 милисекунди.

<h3>отстраняване на неизправности</h3>
<ul>
  <li>Уверете се, че сензорът DHT11 е правилно свързан към Pico дъската.</li>
  <li>Проверете връзките между Pico дъската, 7-сегментния дисплей и сензора DHT11.</li>
  <li>Уверете се, че използвате правилната версия на сензора DHT. В този случай е 11, но може да бъде заменен с 22 или всяка друга подходяща версия.</li>
  <li>Проверете съвместимостта на 7-сегментния дисплей с Pico дъската и нейния интерфейс (I2C или SPI).</li>
</ul>

