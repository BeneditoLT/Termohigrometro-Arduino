# Termohigrometro-Arduino

Instalar Biblioteca


Para realizar este experimento, é preciso que o leitor instale algumas bibliotecas para que o código funcione. As bibliotecas que serão instaladas são a AdafruitSSD1306 e a Adafruit GFX. Portanto, siga os passos descritos abaixo para fazer a instalação. Primeiramente, abra sua IDE e clique em Sketch->Incluir Biblioteca->Gerenciar
Bibliotecas

![webpc-passthru1](https://user-images.githubusercontent.com/46333024/209493623-6a2f9441-a5f9-4d3a-b44f-694ede8dede1.png)

Logo em seguida, faça a busca da biblioteca desejada, adafruit ssd1306, encontre a opção cujo autor é a Adafruit e clique para instalar.

![adafruit-ssd1306](https://user-images.githubusercontent.com/46333024/209493672-b8c90b80-992c-416a-90ee-fa98a1b16778.png)


Feito isso, procure pela segunda biblioteca, adafruit gfx, e instale a opção cujo o autor também é a Adafruit.

![adafruit-gfx](https://user-images.githubusercontent.com/46333024/209493717-197de404-007c-4b64-9531-a0ab3e948cad.png)




Pinout e Características Físicas

Neste post, trabalharemos especificamente com o Display OLED 128×64 0.96″ I2C. O seu pinout é mostrado a segui


![OLED-pinout-diagram-768x768](https://user-images.githubusercontent.com/46333024/209489019-ce2e79d2-3cc2-4ea1-9926-4fb893aa4699.jpg)

GND: Deve ser conectado ao terra do Arduino;
VCC: Fonte de energia do display que deve ser conectada no pino de 5 Volts do Arduino;
SCL: Pino serial de clock da interface I2C;
SDA: Pino serial de dados da interface I2C.

![termohogrometro](https://user-images.githubusercontent.com/46333024/209488667-1fee489c-7244-44d3-bb76-7d544e2c73fc.png)

Programa para gerar imagem 


https://sourceforge.net/projects/lcd-image-converter/files/
