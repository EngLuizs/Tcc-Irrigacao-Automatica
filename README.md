# 🌱 Projeto de Irrigação Automática - IFSP Sertãozinho

Este repositório contém o código-fonte e documentação do Trabalho de Conclusão de Curso (TCC) desenvolvido por alunos do curso Técnico em Eletrônica do Instituto Federal de Educação, Ciência e Tecnologia de São Paulo (IFSP) - Campus Sertãozinho.

## 📌 Descrição

O projeto visa implementar um sistema inteligente de irrigação automática utilizando sensores ambientais e automação com microcontrolador ESP32. O objetivo é otimizar o uso de água em plantações ou hortas, promovendo práticas agrícolas sustentáveis, econômicas e acessíveis à comunidade.

## ⚙️ Funcionalidades

- 💧 Irrigação automática baseada na umidade do solo
- 🌧️ Detecção de chuva para interrupção da irrigação
- ☀️ Controle de luminosidade e temperatura com cúpula móvel
- 📺 Monitoramento local com Display LCD 20x4
- 📱 Comunicação Bluetooth com smartphone
- 📊 Visualização de sensores: umidade, temperatura, luminosidade e chuva

## 🧰 Componentes Utilizados

- [x] ESP32
- [x] Display LCD 20x4 com módulo I2C
- [x] Sensor de umidade do solo
- [x] Sensor de chuva
- [x] Sensor de temperatura LM35
- [x] Sensor de luminosidade LDR
- [x] Micro servo motor MG90S
- [x] Bomba d’água submersa 3V-6V
- [x] Módulo Ponte H (L298N)
- [x] Caixa organizadora, arame galvanizado, tubos PVC, entre outros

## 💻 Tecnologias e Ferramentas

- Arduino IDE
- Linguagem C/C++ (Arduino)
- Comunicação Bluetooth (Serial Bluetooth do ESP32)
- Protoboard e jumpers para montagem de circuito

## 🔧 Como Usar

1. Faça o upload do código `*.ino` para o ESP32 usando a Arduino IDE.
2. Monte o circuito eletrônico conforme o esquema descrito no projeto.
3. Alimente o sistema e conecte via Bluetooth com um aplicativo de controle (ex: Serial Bluetooth Terminal).
4. Os sensores serão lidos automaticamente e as ações (irrigação, cúpula, iluminação) serão executadas conforme os dados coletados.
5. Os dados serão exibidos em tempo real no display LCD.

## 🧪 Testes Realizados

- Testes individuais dos sensores e atuadores
- Integração dos módulos no circuito final
- Simulações de chuva e variações de luz/temperatura
- Testes de vazão da bomba d'água e vedação da estrutura

## 📚 Autores

- Felipe Mantovani  
- Luiz Henrique Luz Santos  
- Marcos Vinicius Soares  
- João Pedro Santana  
- Kaylan Henrique dos Santos  
- Orientador Márcio Bender

## 📅 Ano

2023

## 📝 Licença

Este projeto foi desenvolvido para fins educacionais e está disponível sob a [Licença MIT](LICENSE), permitindo seu uso e modificação com os devidos créditos.

