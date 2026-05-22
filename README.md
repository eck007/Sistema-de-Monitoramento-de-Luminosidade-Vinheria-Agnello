🍷 Vinheria Agnello — Sistema Inteligente de Monitoramento de Vinhos
📖 Sobre o Projeto

A conservação correta dos vinhos é extremamente importante para garantir sua qualidade, sabor e durabilidade. Pequenas mudanças de temperatura, umidade ou luminosidade podem comprometer completamente o armazenamento das garrafas.

Pensando nisso, desenvolvemos um sistema inteligente de monitoramento ambiental para vinherias, adegas e depósitos de armazenamento de vinho.

O projeto utiliza sensores conectados a um Arduino para analisar o ambiente em tempo real e alertar imediatamente quando as condições estiverem inadequadas.

🎯 Qual problema o sistema resolve?

Muitas adegas e depósitos podem sofrer com:

excesso de calor
baixa umidade
iluminação inadequada
falta de monitoramento constante

Esses fatores podem causar:

perda da qualidade do vinho
oxidação
alteração do sabor
prejuízo financeiro

Nosso sistema automatiza esse controle e ajuda a manter o ambiente sempre dentro das condições ideais.

⚙️ Como o sistema funciona?

O sistema monitora continuamente:

🌡️ Temperatura

O sensor identifica se o ambiente está:

muito quente
muito frio
ideal para armazenamento
💧 Umidade

O sistema verifica se o ar está:

seco demais
úmido demais
adequado para conservação
💡 Luminosidade

A iluminação também é monitorada, já que excesso de luz pode prejudicar os vinhos.

🚨 Sistema de Alertas Inteligentes

Quando alguma condição está fora do ideal, o sistema avisa automaticamente através de:

🟢 LEDs Indicadores

Cada cor representa a situação do ambiente:

Verde → Ambiente ideal
Amarelo → Atenção
Vermelho → Situação crítica
🔊 Alerta Sonoro (Buzzer)

Caso o ambiente esteja em situação crítica, um alarme sonoro é ativado.

🖥️ Display LCD

As informações aparecem em tempo real no display:

temperatura atual
umidade atual
status do ambiente
mensagens de alerta
🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido utilizando:

Arduino UNO
Sensor DHT22
Sensor de Luminosidade
Display LCD I2C
LEDs
Buzzer
Linguagem C/C++
📈 Benefícios do Projeto

✅ Monitoramento em tempo real
✅ Redução de perdas de produtos
✅ Maior controle ambiental
✅ Sistema automatizado
✅ Fácil visualização das informações
✅ Baixo custo de implementação
✅ Tecnologia acessível e escalável

🖥️ Simulação do Projeto

O protótipo funcional pode ser acessado online através do Wokwi:

Acessar Simulação no Wokwi

📸 Estrutura do Sistema

Abaixo está a montagem do circuito utilizado no projeto:

![Circuito](./img/circuito.png)
🔄 Funcionamento na Prática

O sistema realiza leituras constantes dos sensores e toma decisões automaticamente.

Exemplo:

Se a temperatura aumentar acima do recomendado:
o LED amarelo acende
o buzzer é ativado
o display informa “Temperatura Alta”

O mesmo acontece para:

umidade inadequada
excesso de luminosidade
💡 Possíveis Aplicações

Este projeto pode ser utilizado em:

vinherias
adegas residenciais
depósitos climatizados
supermercados
restaurantes
distribuidoras de bebidas
👨‍💻 Equipe de Desenvolvimento
Erick Ripari Gomes — RM569441
Guilherme Gimenez — RM563389
Fabricio Denig — RM570980
🎓 Projeto Acadêmico

Projeto desenvolvido para a disciplina de Edge Computing & Computer Systems — FIAP (2026).

📄 Licença

Projeto desenvolvido exclusivamente para fins educacionais.
