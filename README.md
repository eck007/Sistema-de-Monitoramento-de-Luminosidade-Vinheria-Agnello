<div align="center">

# 🍷 Vinheria Agnello Inteligente

### ⚙️ Sistema Inteligente de Monitoramento Ambiental com Arduino

<img src="https://img.shields.io/badge/Arduino-IoT-blue?style=for-the-badge&logo=arduino">
<img src="https://img.shields.io/badge/FIAP-Checkpoint%202-red?style=for-the-badge">
<img src="https://img.shields.io/badge/Status-Funcionando-success?style=for-the-badge">
<img src="https://img.shields.io/badge/Wokwi-Simulation-0096FF?style=for-the-badge">

</div>

---

# 📖 Sobre o Projeto

Imagine uma adega onde o ambiente é monitorado automaticamente 24 horas por dia.

Nosso projeto simula exatamente isso.

A **Vinheria Agnello Inteligente** foi desenvolvida para monitorar fatores essenciais para a conservação dos vinhos:

<div align="center">

🌡️ Temperatura  
💧 Umidade  
💡 Luminosidade  

</div>

---

# ❗ Por que isso é importante?

Vinhos são extremamente sensíveis ao ambiente.

Pequenas alterações podem causar:
- perda da qualidade
- alteração do sabor
- oxidação
- prejuízo financeiro

Por isso criamos um sistema automático capaz de identificar problemas em tempo real.

---

# 🖼️ Projeto Montado

<div align="center">

<img src="Captura de tela 2026-05-22 195603.png" width="850">

### 🔌 Circuito desenvolvido no Wokwi utilizando Arduino UNO + Sensores + LCD + LEDs

</div>

---

# 🧠 Como o Sistema Funciona?

O sistema trabalha em 4 etapas:

---

## 🥇 1. Leitura do Ambiente

Os sensores monitoram constantemente:
- temperatura
- umidade
- luminosidade

---

## 🥈 2. Processamento Inteligente

O Arduino recebe os dados e analisa se o ambiente está:
- ideal
- em alerta
- crítico

---

## 🥉 3. Resposta Automática

Dependendo da situação:
- LEDs são acionados
- mensagens aparecem no LCD
- o buzzer dispara alertas sonoros

---

## 🏁 4. Monitoramento em Tempo Real

Tudo acontece automaticamente e em tempo real.

---

# 🔍 Entendendo os Componentes

---

## 🔌 Arduino UNO

É o cérebro do sistema.

Responsável por:
- processar os dados
- controlar sensores
- ativar LEDs
- mostrar mensagens no display

---

## 🌡️ Sensor DHT22

Responsável por medir:
- temperatura
- umidade

---

## 🌗 Sensor de Luminosidade (LDR)

Mede a quantidade de luz no ambiente.

👉 Quanto maior a luminosidade, maior o risco para os vinhos.

---

## 📟 Display LCD I2C

Mostra:
- temperatura atual
- umidade atual
- status do ambiente
- alertas do sistema

---

## 💡 LEDs Inteligentes

| Cor | Significado |
|---|---|
| 🟢 Verde | Ambiente ideal |
| 🟡 Amarelo | Temperatura fora do ideal |
| 🔴 Vermelho | Umidade/Luminosidade crítica |

---

## 🔊 Buzzer

Dispara um alerta sonoro quando o ambiente entra em situação crítica.

---

# ⚙️ Componentes Utilizados

<div align="center">

| Componente | Função |
|---|---|
| 🔌 Arduino Uno | Controle principal |
| 🌡️ DHT22 | Temperatura e umidade |
| 🌗 LDR | Sensor de luminosidade |
| 📟 LCD I2C | Exibição de informações |
| 💡 LEDs | Alertas visuais |
| 🔊 Buzzer | Alerta sonoro |
| 🧩 Protoboard | Organização do circuito |
| 🔗 Jumpers | Conexões |

</div>

---

# 🚨 Funcionamento do Sistema

## 🌡️ Temperatura

| Situação | Ação |
|---|---|
| 10°C até 15°C | ✅ Temperatura ideal |
| Abaixo de 10°C | ⚠️ Temp. Baixa |
| Acima de 15°C | ⚠️ Temp. Alta |

---

## 💧 Umidade

| Situação | Ação |
|---|---|
| 50% até 70% | ✅ Umidade ideal |
| Abaixo de 50% | 🚨 Umidade baixa |
| Acima de 70% | 🚨 Umidade alta |

---

## 💡 Luminosidade

| Situação | Ação |
|---|---|
| Ambiente escuro | 🟢 LED Verde |
| Meia luz | 🟡 LED Amarelo |
| Ambiente muito claro | 🔴 LED Vermelho + Buzzer |

---

# 🧠 Exemplo da Lógica do Arduino

```cpp
float temperatura = dht.readTemperature();
float umidade = dht.readHumidity();

if (temperatura > 15) {
  // Temperatura alta
}
else if (temperatura < 10) {
  // Temperatura baixa
}
else {
  // Ambiente ideal
}
```

👉 O Arduino toma decisões automáticas utilizando lógica condicional (`if/else`).

---

# 🎯 Objetivos do Projeto

✅ Simular uma adega inteligente  
✅ Trabalhar com sensores reais  
✅ Aplicar conceitos de IoT  
✅ Automatizar monitoramento ambiental  
✅ Desenvolver lógica embarcada  
✅ Criar alertas inteligentes  

---

# 🛠️ Tecnologias Utilizadas

<div align="center">

<img src="https://img.shields.io/badge/Arduino-00979D?style=flat&logo=arduino&logoColor=white">
<img src="https://img.shields.io/badge/Wokwi-0096FF?style=flat">
<img src="https://img.shields.io/badge/C%2B%2B-Language-blue">
<img src="https://img.shields.io/badge/IoT-Internet%20of%20Things-success">

</div>

---

# 🔗 Acesse o Projeto

<div align="center">

## 👉 Simulação no Wokwi

https://wokwi.com/projects/461602074695282689

</div>

---

# 👨‍💻 Equipe de Desenvolvimento

<div align="center">

| Integrante | RM |
|---|---|
| Erick Ripari Gomes | RM569441 |
| Guilherme Gimenez | RM563389 |
| Fabricio Denig | RM570980 |

</div>

---

# 🏫 Contexto Acadêmico

Projeto desenvolvido para o **Checkpoint 02** da disciplina de **Edge Computing** — FIAP 2026.

---

<div align="center">

# 🍷 Obrigado por visitar nosso projeto!

</div>
