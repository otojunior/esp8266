ESP8266 - Projetos
==================

### Instalação do ESP8266 na IDE do Arduino ###

Na IDE do Arduino (usado a 1.8,1 neste roteiro):

1. Menu **Arquivo --> Preferências**
2. No campo **URLS adicionais para gerenciadores de placas** entre com a URL:
`http://arduino.esp8266.com/stable/package_esp8266com_index.json`
3. Menu **Ferramentas --> Placas:... --> Gerenciador de Placas**
4. Procure por **esp8266** e instale.

Link: [Github ESP8266](https://github.com/esp8266/Arduino)

### Instalação do driver da porta COM ###

1. Descompacte e instale o driver presente na pasta **driver** referente ao seu sistema operacional. (Exceto Linux. Neste caso, não precisa instalar nenhumn driver).
2. **_IMPORTANTE_**: Na IDE do Arduino escolher a placa: **WeMos D1 R2 & mini**

Link: [WeMos D1 mini](https://www.wemos.cc/product/d1-mini.html)

### EXTRA - OPCIONAL: Instalação do tema escuro para IDE do Arduino ###

1. Faça um backup da pasta **<Arduino_IDE>/lib/theme**
2. Extraia o arquivo **extras/dark_theme.zip** na pasta **<Arduino_IDE>/lib** sobrescrevendo a pasta **theme** (recomendado: apagar a pasta **theme** antes de extrair).
3. Caso queira voltar com o tema original, basta recuperar o backup.
