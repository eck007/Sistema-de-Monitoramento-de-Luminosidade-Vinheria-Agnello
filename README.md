# Sistema-de-Monitoramento-de-Luminosidade-Vinheria-Agnello

🍷 Sistema de Monitoramento de Luminosidade – Vinheria Agnello

📌 Descrição do Projeto Este projeto tem como objetivo desenvolver um sistema de monitoramento de luminosidade utilizando Arduino, simulando o controle de iluminação em uma vinheria. A luminosidade é um fator importante na conservação do vinho, pois níveis elevados de luz podem comprometer sua qualidade. O sistema criado realiza a leitura da luz ambiente e utiliza LEDs e um buzzer para indicar o estado do ambiente. 

📦 Dependências Para execução do projeto, são necessários os seguintes recursos: - Arduino IDE (ou simulador como Tinkercad/Wokwi) - Navegador web - Conhecimentos básicos de Arduino e eletrônica 

⚙️ Componentes Utilizados - 1 Arduino Uno - 1 Sensor de luminosidade (LDR) - 3 LEDs (verde, amarelo e vermelho) - 3 Resistores (220Ω recomendados) - 1 Buzzer - Protoboard - Jumpers 

🔌 Funcionamento do Sistema O sensor LDR capta a luminosidade do ambiente e envia um valor analógico para o Arduino (variando de 0 a 1023). Com base nesse valor, o sistema classifica o ambiente em três estados: 

🟢 Ambiente OK (luz baixa) - Valor menor que 300 - LED verde aceso - Buzzer desligado 
🟡 Estado de alerta (luz moderada) - Valor entre 300 e 700 - LED amarelo aceso - Buzzer desligado 
🔴 Problema (luz alta) - Valor maior que 700 - LED vermelho aceso - Buzzer é ativado por 3 segundos Caso a luminosidade permaneça alta, o buzzer volta a ser acionado após o intervalo. 

🧠 Lógica do Código O Arduino realiza continuamente a leitura do sensor através do pino analógico A0: int luz = analogRead(sensorLuz); Com base nesse valor, estruturas condicionais (if, else if, else) determinam qual LED será acionado e se o buzzer deve tocar. Quando o nível de luminosidade está acima do permitido, o buzzer é ativado por 3 segundos: digitalWrite(buzzer, HIGH); delay(3000); digitalWrite(buzzer, LOW); 

▶️ Como Reproduzir o Projeto 1. Acesse o Tinkercad (ou Wokwi) 2. Monte o circuito: - LDR no pino A0 - LED verde no pino 10 - LED amarelo no pino 9 - LED vermelho no pino 8 - Buzzer no pino 7 3. Insira o código no Arduino 4. Inicie a simulação 5. Ajuste a luminosidade do LDR para testar 

🎥 Observações Durante o desenvolvimento, foi necessário ajustar os valores de luminosidade (300 e 700) para melhor representar os níveis de iluminação no ambiente simulado. 

✅ Conclusão O projeto atende ao objetivo proposto, permitindo o monitoramento da luminosidade e a geração de alertas visuais e sonoros em situações inadequadas. 

👨‍💻 Integrantes * Erick Ripari Gomes * Fabricio Denig * Guilherme Giménez


Link WORKIWI: https://wokwi.com/projects/461602074695282689

Link Video explicativo:  https://canva.link/4z0kayi19m7t6hj
