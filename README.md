# FECAP - Fundação de Comércio Álvares Penteado

<p align="center">
<a href= "https://www.fecap.br/"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhZPrRa89Kma0ZZogxm0pi-tCn_TLKeHGVxywp-LXAFGR3B1DPouAJYHgKZGV0XTEf4AE&usqp=CAU" alt="FECAP - Fundação de Comércio Álvares Penteado" border="0"></a>
</p>

# Projeto Baseado nos Objetivos de Desenvolvimento Sustentável para monitorar enchentes em Áreas de Risco.

## HydroSecure

## Integrantes: <a href="https://www.linkedin.com/in/alexandra-christine-silva-590092257">Caio Dantas Farias  </a>, <a href="https://linkedin.com/in/hebert-/">Eduardo Araujo de Oliveira	</a>, <a href="https://www.linkedin.com/in/karoline-lemos-540461296/">Saulo Ribeiro Santos	</a>. 
## Professores Orientadores: <a href="https://www.linkedin.com/in/victorbarq/">Victor Bruno Alexander Rosetti de Quiroz</a>.

## ✏ Introdução
![ods](https://github.com/2024-1-NADS1-A/Projeto9/blob/main/imagens/ODS.jpg)
<p align="center">
<img src="![ods](https://github.com/2024-1-NADS1-A/Projeto9/blob/main/imagens/ODS.jpg)" border="0">
  <a> Feito por<a> <a href="https://www.een-portugal.pt/news/PublishingImages/ODS.jpg?Width=500">Objetivos de Desenvolvimento Sustentável (ODS)</a>
</p>

<br> O projeto "Monitoramento de Enchentes em Áreas de Risco" visa reduzir os impactos das enchentes em áreas vulneráveis, utilizando sensores conectados por IoT para monitorar níveis de água e chuvas em tempo real. Com um sistema de alerta precoce, o projeto notificará a população e autoridades sobre riscos iminentes, garantindo uma resposta rápida. Além disso, um dashboard fornecerá dados para decisões informadas, enquanto campanhas de conscientização prepararão as comunidades para agir de forma segura. O objetivo é proteger vidas, minimizar danos e aumentar a resiliência das comunidades em áreas de risco de inundações. </br>

## 🔎 Descrição
![projeto](https://github.com/2024-1-NADS1-A/Projeto9/assets/108402431/77769b33-ea85-45f6-8d60-2b78828086df)


<p align="center">
<img src="![projeto](https://github.com/2024-1-NADS1-A/Projeto9/assets/108402431/77769b33-ea85-45f6-8d60-2b78828086df)" border="0">
  <a> Feito por: <a> <a href="https://www.linkedin.com/in/alexandra-christine-silva-590092257">Alexandra Christine </a>, <a href="https://linkedin.com/in/hebert-/">Hebert dos Reis Esteves	</a>, <a href="https://www.linkedin.com/in/karoline-lemos-540461296/">Karoline Lemos Avelar	</a>, <a href="https://www.linkedin.com/in/matheus-santos-morais/">Matheus Santos Morais	</a>.
</p>


O aumento das enchentes em áreas de risco representa uma séria ameaça à segurança das populações e à sustentabilidade das cidades. Para enfrentar esse desafio, propomos a implementação de um sistema de monitoramento de enchentes utilizando tecnologia IoT (Internet das Coisas), baseada no ESP8266, sensores ultrassônicos para medir os níveis de água e outros componentes para você.

Esse sistema permitirá uma avaliação contínua dos riscos de enchentes, fornecendo dados em tempo real sobre os níveis de água em áreas críticas. As informações serão transmitidas para a plataforma Blynk IoT, que permitirá o monitoramento remoto. A interface do Blynk fornecerá uma visualização acessível e intuitiva, tanto para autoridades quanto para a população, permitindo que eles acompanhem as variações nos níveis de água e identifiquem possíveis riscos de enchimento com

Além de oferecer dados cruciais para a gestão de emergências, o projeto tem como objetivo promover a conscientização sobre a importância da prevenção de desastres naturais. Espera-se que essas informações auxiliem na criação de políticas públicas mais eficazes e em estratégias de planejamento urbano voltadas para a redução dos impactos das enchentes em áreas vulneráveis. Com isso, buscamos minimizar os danos.


## 🛠 Estrutura de pastas

-Raiz<br>
|<br>
|-->documentos<br>
  &emsp;|-->antigos<br>
  &emsp;|Projeto+de+extensão+-+Grupo+°cean_atualizado_com_sensor de turbidez.docx<br>
|-->imagens<br>
|-->src<br>
  &emsp;|-->Backend<br>
  &emsp;|-->Frontend<br>
|readme.md<br>

<b>README.MD</b>: Arquivo que serve como guia e explicação geral sobre seu projeto. O mesmo que você está lendo agora.

Há também 4 pastas que seguem da seguinte forma:

<b>documentos</b>: Toda a documentação estará nesta pasta.

<b>imagens</b>: Imagens do sistema

<b>src</b>: Pasta que contém o código fonte.

## ✔️ Técnicas e tecnologias utilizadas

- ``C++``
- ``Arduino IDE``
- ``Banco de Dados Firebase``
- ``Flutter Flow``

## 📖 Requisitos
![equipamentos](https://github.com/2024-1-NADS1-A/Projeto9/assets/108402431/1d33c70f-3e62-4414-8b26-f7d5601d1520)

<br>🛠 Hardware</br>
 <br>•	ESP8266</br>
 <br>•	Sensor ultrassônico </br>
 <br>•	Sensor de turbidez</br>
 <br>•	Protoboard e Jumpers</br>
 <br>•	Conexão Wi-Fi</br>
<br>💻 Software:</br>
 <br>•	Arduino IDE</br>
 <br>•	Conta no Blynk IOT (para transmissão de dados)</br>
 

## 🛠 Instalação Arduino IDE

<br>•Instale o <a href="https://www.arduino.cc/en/software">Arduino IDE</a> a partir do site oficial.</br>
<br>•	Abra o Arduino IDE após a instalação.</br>

## ⚙Configuração do Arduino IDE para ESP32
<br>•	No Arduino IDE, vá em File > Preferences.</br>
<br>•	Adicione a URL a seguir ao campo "Additional Board Manager URLs"
```sh
https://dl.espressif.com/dl/package_esp32_index.json
````
<br>•	Vá em Tools > Board > Boards Manager, procure por "esp32" e clique em instalar.</br>

## 💻 Instalação de Bibliotecas

<br>•	Firebase ESP Client:</br>
<br>•	Acesse o repositório no GitHub: <a href="https://github.com/mobizt/Firebase-ESP-Client"> Firebase ESP Client</a>.</br>
<br>•	Clique no botão "Code" e selecione "Download ZIP" para baixar a biblioteca em formato .zip.</br>
<br>•	Abra o Arduino IDE.</br>
<br>•	Vá em Sketch > Include Library > Add .ZIP Library....</br>
<br>•	Navegue até o local onde você baixou o arquivo .zip e selecione-o.</br>
<br>•	A biblioteca será adicionada e estará disponível para uso em seus projetos.</br>

 <br><strong>📡WiFi</strong></br>
 <br>•	Vá em Sketch > Include Library > Manage Libraries....</br>
 <br>•	Na caixa de busca, digite "WiFi".</br>
 <br>•	Selecione a biblioteca WiFi para ESP32 e clique em "Install".</br>
 
 ## ⚙Configuração do Hardware

 ## ⚙Configuração do Firebase

 ![firebase](https://github.com/2024-1-NADS1-A/Projeto9/assets/108402431/2dbc1989-21f0-4207-8746-d65eff2a4656)

<br><strong>2.	Defina as credenciais no código:</strong></br>




## ⌨Carregar o Código no ESP82
<br><strong>1.	Conecte o ESP32 ao computador via cabo USB.</strong></br>
<br><strong>2.	No Arduino IDE, selecione a placa e a porta correspondente ao ESP32:</strong></br>
 <br>•	Vá em Tools > Board e selecione "DOIT ESP32 DEVKIT V1".</br>
 <br>•	Vá em Tools > Port e selecione a porta onde o ESP32 está conectado.</br>
<br><strong>3.	Clique em Upload para carregar o código no ESP32.</strong></br>

## 💻Monitoramento
<br>•	Abra o Serial Monitor (Ctrl + Shift + M) para ver os dados de depuração e confirmar se o ESP32 está conectando ao Wi-Fi e enviando dados ao Firebase corretamente.</br>

## 📱Conexão com o Aplicativo desenvolvido no Flutter Flow
<br>Para visualizar os dados do sensor em um aplicativo móvel, vamos configurar o Flutter Flow e conectá-lo ao Firebase.</br>
<br><strong>1. Requisitos</strong></br> 
 <br>•	Conta no Flutter Flow</br>
 <br>•	Conexão Wi-Fi</br>
 <br>•	Conta no Firebase</br>
## 📱Passo a Passo para Configuração do Flutter Flow
<br><strong>1.	Criar Conta no Flutter Flow:</strong></br>
 <br>•	Vá para o site do <a href="https://flutterflow.io">Flutter Flow</a> e crie uma conta.</br>
 
<br><strong>2.	Configurar Projeto no Flutter Flow:</strong></br>
 <br>•	Após criar uma conta, clique em Create New Project.</br>
 <br>•	Dê um nome ao seu projeto e escolha um template de sua preferência.</br>
 
<br><strong>3.	Conectar ao Firebase:</strong></br>
 <br>•	No painel do Flutter Flow, vá para a seção Settings e clique em Firebase.</br>
 <br>•	Siga as instruções para conectar seu projeto Firebase ao Flutter Flow.</br>
 <br>•	Adicione a URL da sua API, a chave do projeto, e outras credenciais do Firebase.</br>

<br><strong>4.	Configurar Coleções no Firebase</strong></br>
<br><strong>5.	Design das Telas no Flutter Flow:</strong></br>
 <br>•	Crie uma nova tela para exibir os dados do sensor.</br>
 <br>•	Adicione widgets de texto para mostrar os valores de temperatura, turbidez, condição da água, data e horário.</br>
 <br>•	Configure cada widget de texto para puxar dados do Firebase configurando as respectivas referências aos campos da coleção leitura.</br>
<br><strong>6.	Configurar Tela de Notícias:</strong></br>
 <br>•	Crie uma nova tela para exibir notícias sobre a água.</br>
 <br>•	Adicione widgets de texto ou cards para exibir títulos e descrições de notícias sobre a qualidade da água.</br>
 <br>•	Insira conteúdo estático ou conecte-se a uma coleção no Firebase que contenha notícias.</br>
<br><strong>7.	Pré-visualização e Testes:</strong></br>
 <br>•	Use o modo de pré-visualização do Flutter Flow para testar seu aplicativo.</br>
 <br>•	Certifique-se de que os dados do Firebase estão sendo corretamente exibidos e atualizados no aplicativo.</br>
<br><strong>8.	Publicação:</strong></br>
 <br>•	Após testar e garantir que tudo está funcionando, vá em App Settings, depois vá em Web Publishing e clique em Publish.</br>
 <br>•	Será gerado um link, como por exemplo: https://ocean-novinho-l5apv0.flutterflow.app/.</br>
 <br>•	Gere um atalho para simular um app.</br>

<table>
  <tr>
    <td><img src="https://github.com/2024-1-NADS1-A/Projeto9/assets/108402431/7f07536f-68a6-4bce-b40e-aa7eb00992b9" width="300"/></td>
    <td><img src="https://github.com/2024-1-NADS1-A/Projeto9/assets/108402431/b702c91a-ab04-486b-9fdb-8d169a772b55" width="300"/></td>
    <td><img src="https://github.com/2024-1-NADS1-A/Projeto9/assets/108402431/5ba3e0b6-dd68-4284-b306-570d78801220" width="300"/></td>
    <td><img src="https://github.com/2024-1-NADS1-A/Projeto9/assets/108402431/4866f771-8f48-4088-9257-413d146f70d1" width="300"/></td>
  </tr>
</table>


## 🗃 Histórico de lançamentos

* 0.2.1 - 21/05/2024
    * CONSERTADO: Correção no Bug da turbidez  (Hebert)
* 0.2.0 - 21/05/2024
    * MUDANÇA: Compra da caixa organizadora (Alexandra)
* 0.1.1 - 23/05/2024
    * CONCLUÍDO: Atualização da Pesquisa de Extensão (Matheus e Karoline)
* 0.1.0 - 24/05/2024
    * CONCLUÍDO: Criação do README (Hebert e Alexandra)

## 📋 Licença/License

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/2024-1-NADS1-A/Projeto9">Ocean</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/2024-1-NADS1-A/Projeto9">FECAP, Alexandra Christine Silva Raimundo, Hebert dos Reis Esteves, Karoline Lemos Avelar, Matheus Santos Morais.</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Creative Commons Attribution 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>


## 🎓 Referências

Aqui estão as referências usadas no projeto.

1. MSC (Marine Stewardship Council). Oceanos em risco: Alterações climáticas e pesca. Disponível em: https://tinyurl.com/2nb87ddw Acesso em: 25 abr.2024.
2. CNN Brasil. Aquecimento dos oceanos está em níveis recordes há um ano; entenda o risco. Disponível em: https://tinyurl.com/4f4377f3.Acesso em: 25 abr. 2024.
3. Como usar um Sensor de Nível de Água. Disponível em: https://tinyurl.com/4a77w3kx. Acesso em: 25 abr. 2024.
4. Maretório: o impacto da maré nos territórios de comunidades costeiras. Disponível em: https://tinyurl.com/4htym3nc. Acesso em: 25 abr. 2024.
5. Efeitos do aquecimento global ameaçam vida marinha. Disponível em: https://tinyurl.com/bdcfmnnr. Acesso em: 25 abr. 2024.
6. Paulo Horta et a. Mudanças Climáticas e a zona costeira do Brasil: vulnerabilidades socioambientais e estratégias de ação. Vol.11.3, dez/2020. Disponível em: https://tinyurl.com/mrxezh7w. Acesso em: 25 abr. 2024.
7. Random Nerd Tutorials. ESP32 with DS18B20 Temperature Sensor using Arduino IDE. Disponível em: https://randomnerdtutorials.com/esp32-ds18b20-temperature-arduino-ide/. Acesso em: 22 maio 2024.
8. Blog da Robótica. Como utilizar o módulo sensor de turbidez de partículas suspensas na água com Arduino. Disponível em: https://www.blogdarobotica.com/2023/01/10/como-utilizar-o-modulo-sensor-de-turbidez-de-particulas-suspensas-na-agua-com-arduino/. Acesso em: 22 maio 2024.
9. TFK IoT Blog. Send DHT11 Sensor Data to Firebase. Disponível em: https://tfkiot.blogspot.com/2023/12/send-dht11-sensor-data-to-firebase.html. Acesso em: 22 maio 2024.
10. TFK IoT GitHub. Esp32-Esp8266_Send_DHT11_Data_To_FireStore. Disponível em: https://github.com/tfkiot/Esp32-Esp8266_Send_DHT11_Data_To_FireStore/tree/main. Acesso em: 22 maio 2024.
