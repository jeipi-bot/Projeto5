# FECAP - Fundação de Comércio Álvares Penteado

<p align="center">
<a href= "https://www.fecap.br/"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhZPrRa89Kma0ZZogxm0pi-tCn_TLKeHGVxywp-LXAFGR3B1DPouAJYHgKZGV0XTEf4AE&usqp=CAU" alt="FECAP - Fundação de Comércio Álvares Penteado" border="0"></a>
</p>

# Projeto Baseado nos Objetivos de Desenvolvimento Sustentável para monitorar enchentes em Áreas de Risco.

## HydroSecure

## Integrantes: <a href="https://www.linkedin.com/in/caio-dantas-5bb171329/">Caio Dantas Farias  </a>, <a href="https://www.linkedin.com/in/eduardo-araujo-33a1a2278/">Eduardo Araujo de Oliveira	</a>, <a href="https://www.linkedin.com/in/saulo-santos-a1ba86334/">Saulo Ribeiro Santos	</a>. 
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
  <a> Feito por: <a> <a href="https://www.linkedin.com/in/caio-dantas-5bb171329/">Caio Dantas Farias </a>, <a href="https://www.linkedin.com/in/eduardo-araujo-33a1a2278/">Eduardo Araujo de Oliveira</a>,<a href="https://www.linkedin.com/in/saulo-santos-a1ba86334/">Saulo Ribeiro Santos	</a>.
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
- ``Blynk IOT``

## 📖 Requisitos
![image](https://github.com/user-attachments/assets/e6d2bfdc-fc2a-47af-86d4-d134264c83af)


<br>🛠 Hardware</br>
 <br>•	ESP8266</br>
 <br>•	Sensor ultrassônico </br>
 <br>•	Protoboard e Jumpers</br>
 <br>•	Recipiente (Reservatório) </br>
<br>💻 Software:</br>
 <br>•	Arduino IDE</br>
 <br>•	Conta no Blynk IOT (para transmissão de dados)</br>
 

## 🛠 Instalação Arduino IDE

<br>•Instale o <a href="https://www.arduino.cc/en/software">Arduino IDE</a> a partir do site oficial.</br>
<br>•	Abra o Arduino IDE após a instalação.</br>

## ⚙Configuração do Arduino IDE para ESP82
<br>•	No Arduino IDE, vá em File > Preferences.</br>
<br>•	Adicione a URL a seguir ao campo "Additional Board Manager URLs"
```sh
https://dl.espressif.com/dl/package_esp32_index.json
````
<br>•	Vá em Tools > Board > Boards Manager, procure por "esp82" e clique em instalar.</br>

## 💻 Instalação de Bibliotecas
<br>• Baixe as bibliotecas Sketch -> Include Library -> Menage Libraries -> pesquise por Blynk e instale.</br>
<br>• Instale o drive CP210x Universal Windows Driver no site Silicon Labs</br>
<br>• No Arduino IDE, vá em File > Preferences.</br>
<br>• Adicione a URL a seguir ao campo "Additional Board Manager URLs"
 
 ## ⚙Configuração do Blynk IOT
 <br>• Entre no site do Blykn e faça login:https://blynk.io/</br>
<br>• Crie um novo projeto e obtenha as credenciais com o token de autenticação;</br>
<br>• No código do ESP82 inclua a biblioteca do Blynk e insira as credenciais;</br>
<br>• Estabeleça a conexão com o servidor do Blynk;</br>
<br>• Configure os pinos virtuais;</br>
<br>• Com a conexão, integre o ES82 ao Blynk;</br>
<br>• Coloque o ESP82 online;</br>
<br>• Execute atualizações de firmaware OTA;</br>
<br>• Contrua a Interface;</br>
<br>• Configure o modelo, alertas, notificações e automações;</br>
<br>• Após todas as etapas a integração e interface estará pronta.</br>


## ⌨Carregar o Código no ESP82
<br><strong>1.	Conecte o ESP82 ao computador via cabo USB.</strong></br>
<br><strong>2.	No Arduino IDE, selecione a placa e a porta correspondente ao ESP82:</strong></br>
 <br>•	Vá em Tools > Board e selecione "DOIT ESP82 DEVKIT V1".</br>
 <br>•	Vá em Tools > Port e selecione a porta onde o ESP82 está conectado.</br>
<br><strong>3.	Clique em Upload para carregar o código no ESP82.</strong></br>

## 💻Monitoramento
<br>•	Abra o Serial Monitor (Ctrl + Shift + M) para ver os dados de depuração e confirmar se o ESP82 está conectando ao Wi-Fi e enviando dados ao Blynk IOT corretamente.</br>


## 🗃 Histórico de lançamentos

* 0.1.0 - 10/10/2024 CONCLUÍDO: Compra de materiais (Caio) 
* 0.2.0 - 12/10/2024 CONCLUÍDO: Template (Eduardo) 
* 0.3.0 - 23/05/2024 CONCLUÍDO: Teste de sensores (Todos)
* 0.4.0 - 07/11/2024 ANDAMENTO: Organização do github e pastas (Saulo)
* 0.5.0 - 05/11/2024 ANDAMENTO: Desenvolvimento do código e circuito (Todos)
* 0.6.0 - 12/11/2024 ANDAMENTO: Integração ao Blynk (Todos)
    

## 📋 Licença/License
<p xmlns:cc="http://creativecommons.org/ns#" >Este trabalho está licenciado sob <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>

## 🎓 Referências

Aqui estão as referências usadas no projeto.
