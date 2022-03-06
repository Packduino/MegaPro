# MegaPro CPU
Sistema de Automação de Médio Porte com 64 portas configuráveis como entrada ou saída utilizando Arduino Mega pro e comunicação WIFI opcional com ESP01 ou ESP12 (D1 MINI).
<br>
Este projeto foi pensado para pessoas interessadas em montar sua própria automação residencial ou industrial, porém com pouca prática em confecção de placas.
<p>
O Sistema completo conta com uma placa principal (Arduino Mega Pro), oito placas optoacopladoras para proteção da CPU e placas para conexão com módulos de 8 relés.
  

 <h3> Principais características: </h3>
 <br>- 64 portas configuráveis como entrada ou saídas divididos em 8 módulos com 8 portas;
 <br> - Fácil programação via Arduino IDE (utiliza um Arduino Mega);
 <br> - Controle via WIFI opcional(com um Esp01 ou Esp12);
 <br> - Testado com MQTT e acesso via OpenHab e Homeassistant;
 <br> - Fácil implementação de controle por comando de voz (Alexa e Google Home);
 <br> - Sistema de RF 433 MHz disponível para controle de portões e cortinas automáticas;
 <br> - Fácil manutenção pois todas as conexões dos cabos utilizam conectores RJ45;
 <br> - Controladores conectados por encaixe na CPU;
 
<h2> Placa finalizada </h2>
<br> Esp01 para comunicação WIFI
  <img src="https://github.com/Packduino/MegaPro/blob/main/foto_esp01.png" alt="Sistema com Esp01" width="600" height="600">
<br> Esp12 para comunicação WIFI
  <img src="https://github.com/Packduino/MegaPro/blob/main/foto_esp12.png" alt="Sistema com Esp12" width="600" height="600">
<h2> Projetos dos PCBs </h2>
<table border="1">
    <tr>
        <td>Placa</td>
        <td>Projeto</td>
        <td>PCB Pronto</td>
    </tr>
    <tr>
        <td>CPU</td>
        <td><img src="https://github.com/Packduino/MegaPro/blob/main/frente.png" alt="CPU 3D" width="400" height="400"></td>
        <td><img src="https://github.com/Packduino/MegaPro/blob/main/fundo.png" alt="CPU REAL" width="400" height="400"></td>
    </tr>
    <tr>
        <td>Opto Acoplador</td>
        <td><img src="https://github.com/Packduino/Esp32Mega/blob/main/Esp32Mega_OPTO_clean.png" alt="OPTO 3D" width="200" height="130"></td>
        <td><img src="https://github.com/Packduino/Esp32Mega/blob/main/Esp32Mega_OPTO_foto.png" alt="OPTO REAL" width="200" height="130"></td>
    </tr>
    <tr>
        <td>Conector Relé</td>
        <td><img src="https://github.com/Packduino/Esp32Mega/blob/main/Esp32Mega_RELE_clean.png" alt="OPTO 3D" width="200" height="200"></td>
        <td><img src="https://github.com/Packduino/Esp32Mega/blob/main/Esp32Mega_RELE_FOTO.png" alt="OPTO REAL" width="200" height="200"></td>
    </tr>
</table>
