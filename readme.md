# STM32 Photo Trap Project

Projekt fotopułapki z wykorzystaniem mikrokontrolera STM32. Moduł czujnika odległości HC-SR04 pozwala na odczyt aktualnego dystansu od obietku, jeśli odległość wynosi poniżej 100cm wykonane jest zdjęcie przy pomocy kamerki OV7670 VGA 640x480.
Zdjęcie zapisywane jest na karcie SD, po czym wysyłany jest komunikat przez USB-UART o wykryciu obiektu i wykonaniu zdjęcia.

## Project photos, modules connected to STM32

![Image of STM](/images/1.png)
![Image of STM](/images/2.png)
![Image of STM](/images/3.png)
![Image of STM](/images/4.png)
![Image of STM](/images/5.png)
![Image of STM](/images/6.png)
![Image of STM](/images/stm1.png)
![Image of STM](/images/stm2.png)

## Usage

Projekt wymaga jedynie zasilania przez USB, po wgraniu oprogramowania na płytkę. IDE Cube32 pozwala na dogłębną analizę funkcjonowania systemu w czasie rzeczywistym.
