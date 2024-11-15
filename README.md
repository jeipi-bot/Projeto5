# FECAP - Fundação de Comércio Álvares Penteado

<p align="center">
  <a href="https://www.fecap.br/">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhZPrRa89Kma0ZZogxm0pi-tCn_TLKeHGVxywp-LXAFGR3B1DPouAJYHgKZGV0XTEf4AE&usqp=CAU" 
         alt="FECAP - Fundação de Comércio Álvares Penteado" border="0">
  </a>
</p>

---

# 🌎 HydroSecure
## Projeto Baseado nos Objetivos de Desenvolvimento Sustentável para monitorar enchentes em Áreas de Risco.

### **Integrantes**:
- [Caio Dantas Farias](https://www.linkedin.com/in/caio-dantas-5bb171329/)
- [Eduardo Araujo de Oliveira](https://www.linkedin.com/in/eduardo-araujo-33a1a2278/)
- [Saulo Ribeiro Santos](https://www.linkedin.com/in/saulo-santos-a1ba86334/)

### **Professor Orientador**:
- [Victor Bruno Alexander Rosetti de Quiroz](https://www.linkedin.com/in/victorbarq/)

---

<div align="center">

## ✏ Introdução

![ODS](https://github.com/2024-1-NADS1-A/Projeto9/blob/main/imagens/ODS.jpg)

<a href="https://www.een-portugal.pt/news/PublishingImages/ODS.jpg?Width=500">
Objetivos de Desenvolvimento Sustentável (ODS)
</a>

</div>

O projeto **HydroSecure** visa reduzir os impactos das enchentes em áreas vulneráveis por meio de sensores conectados via IoT. Ele monitora níveis de água e chuvas em tempo real, enviando alertas para a população e autoridades sobre riscos iminentes, promovendo uma resposta rápida. Além disso, um dashboard fornece dados para decisões informadas, e campanhas de conscientização preparam as comunidades para agir de forma segura. O objetivo é proteger vidas, minimizar danos e aumentar a resiliência das comunidades em risco de inundações.

---

<div align="center">

## 🔎 Descrição

![Descrição](https://github.com/user-attachments/assets/0be2721f-3045-4204-9a1c-9a73c3f5ace5)

</div>

O **HydroSecure** utiliza tecnologia IoT, incluindo **ESP32**, sensores ultrassônicos e componentes elétricos para monitorar riscos de enchentes. O sistema coleta dados em tempo real, transmitindo-os para a plataforma **Blynk IoT**, que permite monitoramento remoto por uma interface intuitiva. Com isso, autoridades e comunidades podem acompanhar níveis de água e adotar medidas preventivas. Além de promover segurança, o projeto visa apoiar políticas públicas para a gestão de desastres naturais.

---

<div align="center">

## 📱 Telas do Blynk IoT

<img src="https://github.com/user-attachments/assets/0e1ab97a-b10c-445d-b91f-cd3f0429f628" alt="Tela 1" width="45%">
<img src="https://github.com/user-attachments/assets/48ad0ecd-a942-49cd-a169-aba2fe408de9" alt="Tela 2" width="45%">

</div>

### **Funcionalidades do Dashboard**
1. **Visualização em Tempo Real**:
   - Gráficos dinâmicos para monitorar dados como níveis de água.
2. **Controle de Dispositivos**:
   - Ativação e desativação de sensores.
3. **Alertas Automáticos**:
   - Notificações push em caso de riscos iminentes.
4. **Histórico de Dados**:
   - Registros para análise de tendências.

---

## 🛠 Estrutura de Pastas

```plaintext
Raiz/
├── documentos/
│   ├── antigos/
│   └── Projeto+de+extensão.docx
├── imagens/
├── src/
│   ├── Backend/
│   └── Frontend/
└── README.md

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
![image](https://github.com/user-attachments/assets/b7d1debe-fba1-4727-889b-dd0fab4178bb)


<br>🛠 Hardware</br>
 <br>•	ESP32</br>
 <br>•	Sensor ultrassônico </br>
 <br>•	Protoboard e Jumpers</br>
 <br>•	Recipiente (Reservatório) </br>

 
 <br>💻  Software:</br>
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
<br>• Baixe as bibliotecas Sketch -> Include Library -> Menage Libraries -> pesquise por Blynk e instale.</br>
<br>• Instale o drive CP210x Universal Windows Driver no site Silicon Labs</br>
<br>• No Arduino IDE, vá em File > Preferences.</br>
<br>• Adicione a URL a seguir ao campo "Additional Board Manager URLs"
 
 ## ⚙Configuração do Blynk IOT
<br>• Entre no site do Blykn e faça login:https://blynk.io/</br>
<br>• Crie um novo projeto e obtenha as credenciais com o token de autenticação;</br>
<br>• No código do ESP32 inclua a biblioteca do Blynk e insira as credenciais;</br>
<br>• Estabeleça a conexão com o servidor do Blynk;</br>
<br>• Configure os pinos virtuais;</br>
<br>• Com a conexão, integre o ESP32 ao Blynk;</br>
<br>• Coloque o ESP32 online;</br>
<br>• Execute atualizações de firmaware OTA;</br>
<br>• Contrua a Interface;</br>
<br>• Configure o modelo, alertas, notificações e automações;</br>
<br>• Após todas as etapas a integração e interface estará pronta.</br>


## ⌨Carregar o Código no ESP32
<br><strong>1.	Conecte o ESP32 ao computador via cabo USB.</strong></br>
<br><strong>2.	No Arduino IDE, selecione a placa e a porta correspondente ao ESP32:</strong></br>
 <br>•	Vá em Tools > Board e selecione "DOIT ESP32 DEVKIT V1".</br>
 <br>•	Vá em Tools > Port e selecione a porta onde o ESP32 está conectado.</br>
<br><strong>3.	Clique em Upload para carregar o código no ESP32.</strong></br>

## 💻Monitoramento
<br>•	Abra o Serial Monitor (Ctrl + Shift + M) para ver os dados de depuração e confirmar se o ESP32 está conectando ao Wi-Fi e enviando dados ao Blynk IOT corretamente.</br>


## 🗃 Histórico de lançamentos

* 0.1.0 - 10/10/2024 CONCLUÍDO: Compra de materiais (Caio) 
* 0.2.0 - 12/10/2024 CONCLUÍDO: Template (Eduardo) 
* 0.3.0 - 23/05/2024 CONCLUÍDO: Teste de sensores (Todos)
* 0.4.0 - 05/11/2024 CONCLUÍDO: Organização do github e pastas (Saulo)
* 0.5.0 - 07/11/2024 CONCLUÍDO: Desenvolvimento do código e circuito (Todos)
* 0.6.0 - 08/11/2024 CONCLUÍDO: Documentação do projeto (Caio)
* 0.7.0 - 12/11/2024 CONCLUÍDO: Integração ao Blynk (Todos)
* 0.8.0 - 16/11/2024 CONCLUÍDO: Conclusão do projeto. 
    

## 📋 Licença/License
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/2024-2-NADS1/Projeto5">HydroSecure</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>

## 📋 Referências 
- https://youtu.be/AOnQOy_VnX8?si=LKmRel0goavLuQgR
- https://encurtador.com.br/U3AQh
- https://encurtador.com.br/NfqyE
- https://youtu.be/rcHlh4b2L1w?si=FsobuTLUKd0_Dysg
- https://youtu.be/rTk5pmnjdnk?si=sUUzsX75xAjpHkK-
- https://youtu.be/WBbMHWQwWlY?si=ZKQ65R3WOSuMdFnD
- https://randomnerdtutorials.com/

