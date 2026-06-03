<div align="center">

# 📡 AstraNode

### ⚙️ Estação Inteligente de Monitoramento de Conectividade Via Satélite

<img src="https://img.shields.io/badge/Arduino-Edge%20Computing-blue?style=for-the-badge&logo=arduino">
<img src="https://img.shields.io/badge/FIAP-Global%20Solution-red?style=for-the-badge">
<img src="https://img.shields.io/badge/Wokwi-Simulation-0096FF?style=for-the-badge">
<img src="https://img.shields.io/badge/IoT-Connected-success?style=for-the-badge">

</div>

---

# 📖 Sobre o Projeto

Imagine uma comunidade rural que depende integralmente de internet via satélite para realizar atividades essenciais como aulas remotas, telemedicina, agricultura digital e acesso a serviços públicos.

Quando ocorrem falhas de conectividade, muitas vezes não existem ferramentas simples que permitam identificar rapidamente o problema e auxiliar na tomada de decisão.

O **AstraNode** foi desenvolvido para simular uma estação inteligente de monitoramento de conectividade via satélite, capaz de acompanhar a qualidade da conexão, identificar situações críticas, gerar alertas e auxiliar na priorização de serviços essenciais.

O projeto faz parte da solução **AstraLink**, plataforma criada para apoiar a gestão da conectividade em comunidades remotas.

---

# ❗ Por que isso é importante?

A conectividade é um fator essencial para o desenvolvimento social e econômico de regiões afastadas.

Falhas de comunicação podem impactar diretamente:

<div align="center">

🏫 Educação

🏥 Saúde

🌾 Agricultura

🌎 Inclusão Digital

📡 Comunicação de Emergência

</div>

Por isso, foi desenvolvido um sistema capaz de transformar informações técnicas de conectividade em alertas simples e acionáveis.

---

# 🖼️ Projeto Montado

<div align="center">

<img src="astranode-print.png" width="850">

### 📡 Circuito desenvolvido no Wokwi utilizando Arduino UNO, LCD, LEDs, Buzzer e Sensores Simulados

</div>

---

# 🎯 Objetivo da Solução

O AstraNode tem como objetivo monitorar condições de conectividade em comunidades remotas conectadas via satélite, permitindo identificar falhas, gerar alertas e auxiliar gestores na priorização de recursos críticos.

A solução busca demonstrar como tecnologias de Edge Computing podem apoiar a gestão da infraestrutura digital em regiões que dependem de comunicações espaciais.

---

# 🧠 Como o Sistema Funciona?

O sistema trabalha em cinco etapas principais.

---

## 🥇 1. Monitoramento da Conectividade

O sistema realiza a leitura contínua dos indicadores simulados:

* qualidade do sinal via satélite;
* quantidade de usuários conectados;
* prioridade operacional da rede.

---

## 🥈 2. Processamento Inteligente

O Arduino processa as informações recebidas e calcula um índice de conectividade.

Com base nos valores monitorados, a rede é classificada como:

* Estável;
* Instável;
* Crítica.

---

## 🥉 3. Priorização de Serviços

O sistema permite alternar entre diferentes prioridades operacionais:

* Educação;
* Saúde;
* Agricultura;
* Uso Geral.

Cada prioridade utiliza critérios específicos para avaliar a qualidade da rede.

---

## 🏅 4. Simulação de Eventos Solares

O AstraNode simula interferências causadas por eventos solares, representando situações que podem impactar comunicações via satélite.

Durante esses eventos, a qualidade da conexão é reduzida e alertas são gerados automaticamente.

---

## 🏁 5. Monitoramento em Tempo Real

Todas as informações são processadas e apresentadas em tempo real através de LEDs, display LCD e alertas sonoros.

---

# 🔍 Entendendo os Componentes

---

## 🔌 Arduino UNO

É o cérebro do sistema.

Responsável por:

* processar os dados;
* controlar LEDs;
* gerar alertas;
* exibir informações no LCD;
* executar toda a lógica do projeto.

---

## 🎛️ Potenciômetro 1

Simula a intensidade do sinal da internet via satélite.

Quanto maior o valor, melhor a qualidade da conexão.

---

## 👥 Potenciômetro 2

Simula a quantidade de usuários conectados à rede.

Quanto maior o número de usuários, maior o consumo da infraestrutura disponível.

---

## 📟 Display LCD I2C

Exibe:

* comunidade monitorada;
* status da conexão;
* prioridade operacional;
* alertas do sistema;
* eventos solares.

---

## 💡 LEDs Inteligentes

| Cor         | Significado             |
| ----------- | ----------------------- |
| 🟢 Verde    | Rede Estável            |
| 🟡 Amarelo  | Rede Instável           |
| 🔴 Vermelho | Rede Crítica            |
| 🟠 Laranja  | Alteração de Prioridade |

---

## 🔊 Buzzer

Responsável por emitir alertas sonoros sempre que situações críticas forem identificadas.

---

## 🔘 Botão de Controle

Permite alternar entre as prioridades operacionais monitoradas pelo sistema.

---

# ⚙️ Componentes Utilizados

<div align="center">

| Componente        | Função                   |
| ----------------- | ------------------------ |
| 🔌 Arduino Uno    | Controle principal       |
| 📟 LCD I2C        | Exibição das informações |
| 🎛️ Potenciômetro | Simulação do sinal       |
| 👥 Potenciômetro  | Simulação de usuários    |
| 💡 LEDs           | Alertas visuais          |
| 🔊 Buzzer         | Alerta sonoro            |
| 🔘 Push Button    | Controle de prioridade   |
| 🧩 Protoboard     | Organização do circuito  |
| 🔗 Jumpers        | Conexões                 |

</div>

---

# 🚨 Funcionamento do Sistema

## 📡 Qualidade da Conexão

| Situação      | Ação                     |
| ------------- | ------------------------ |
| Rede Estável  | 🟢 LED Verde             |
| Rede Instável | 🟡 LED Amarelo           |
| Rede Crítica  | 🔴 LED Vermelho + Buzzer |

---

## 🏫 Prioridades Operacionais

| Prioridade  | Objetivo                                |
| ----------- | --------------------------------------- |
| Educação    | Garantir aulas e conteúdos online       |
| Saúde       | Priorizar telemedicina e atendimentos   |
| Agricultura | Suportar sensores e monitoramento rural |
| Geral       | Utilização padrão da rede               |

---

## ☀️ Evento Solar

Durante a simulação de eventos solares:

* a qualidade da conexão é reduzida;
* o sistema gera alertas;
* o monitoramento registra possíveis impactos na rede.

---

# 🧠 Exemplo da Lógica Utilizada

```cpp
int indice = sinal - (usuarios / 2);

if (indice >= limiteVerde) {
  // Rede Estável
}
else if (indice >= limiteAmarelo) {
  // Rede Instável
}
else {
  // Rede Crítica
}
```

O Arduino toma decisões automaticamente utilizando lógica condicional e processamento local dos dados.

---

# 🛠️ Tecnologias Utilizadas

<div align="center">

<img src="https://img.shields.io/badge/Arduino-00979D?style=flat&logo=arduino&logoColor=white">

<img src="https://img.shields.io/badge/Wokwi-0096FF?style=flat">

<img src="https://img.shields.io/badge/C%2B%2B-Language-blue">

<img src="https://img.shields.io/badge/IoT-Internet%20of%20Things-success">

<img src="https://img.shields.io/badge/Edge%20Computing-FIAP-red">

</div>

---

# 🔗 Acesse o Projeto

<div align="center">

## 👉 Simulação no Wokwi

COLOCAR_LINK_WOKWI

## 👉 Vídeo Explicativo

COLOCAR_LINK_VIDEO

</div>

---

# 👨‍💻 Equipe de Desenvolvimento

<div align="center">

| Integrante    | RM |
| ------------- | -- |
| Beatriz Perigo | 569654 |
| Fabricio Denig | 570980 |
| Rafael Sobral | 569527 |

</div>

---

# 🏫 Contexto Acadêmico

Projeto desenvolvido para a **Global Solution 2025** da disciplina de **Edge Computing & Computer Systems** da FIAP.

A solução foi criada com o objetivo de demonstrar a aplicação de conceitos de Edge Computing, IoT e monitoramento inteligente em cenários de conectividade via satélite para comunidades remotas.

---

<div align="center">

# 📡 Obrigado por visitar o AstraNode!

### Conectando comunidades através da tecnologia espacial.

</div>
