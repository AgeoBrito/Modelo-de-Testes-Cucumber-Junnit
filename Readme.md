## Utilizando Junit/Cucumber 

## ⚙️ Ferramentas utilizadas 

* Cucumber
* Junnit
* Eclipse Ide

## 💬 Sobre
Exemplo do uso das ferramentas Cucumber e Junnit, operando dois cenários com 4 testes embutidos.

## Features e Cenários
* Feature: Cliente faz saque de dinheiro como um cliente, eu gostaria de sacar dinheiro em caixa eletrônico,
para que eu não tenha que esperar numa fila de banco.

* Cenário 1: Cliente especial com saldo negativo
Given - Um cliente especial com saldo atual de -200 reais 
When - For solicitado um saque no valor de 100 reais
Then - Deve efetuar o saque e atualizar o saldo da conta para -300 reais

* Cenário 2: Cliente comum com saldo negativo
Given - Um cliente comum com saldo atual de -300 reais
When - Solicitar um saque de 200 reais
Then - Não deve efetuar o saque e deve retornar a mensagem Saldo Insuficiente

## 🚀 Como Acessar?
Para poder usar o projeto em sua máquina, siga os seguintes passos.
1. Baixe o arquivo e descompate em sua Máquina
2. Abra o Eclipse IDE e Abra a pasta descompactada
- Clique em File
- Após clique em Open Projects from Files system
- Clique em directory
- Escolha a pasta descompactada
- Clique em Finish após tudo isso.
3. Instale o Cucumber no Eclipse
- Clique em Help
- Clique logo após em Eclipse Marketplace
- No campo Find escreva 'Cucumber'
- Clique em Install 
4. Agora poderá rodar a bateria de teste.


##  ♦Feito por♦
- Luiz Ageo - Contato: luizageu3@gmail.com.

## ♦ Muito Obrigado ♦

