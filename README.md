# 🖥️ Lan-House - Projeto Integrador

## 📌 Sobre o Projeto
Este projeto tem como objetivo montar uma Lan-House completa, utilizando computadores antigos, com sistema operacional Linux, simulando como funcionavam as lan houses antigas, mas com tecnologia atual e de baixo custo.

A ideia é reviver a experiência das lan houses, onde as pessoas se reuniam para jogar em rede, com controle de tempo por computador.

## 🎯 Objetivo
- Montar uma rede local com 8 PCs + 1 servidor
- Instalar Linux em PCs antigos para reaproveitamento
- Instalar e configurar o jogo Urban Terror para jogar em rede
- Utilizar o Timer Café no servidor para controlar o tempo de uso de cada PC
- Proporcionar uma experiência de lan house real

## 🛠️ O que iremos utilizar
- 8 Computadores Positivo (antigos)
- 1 Computador para Servidor
- Switch / Roteador para interligar os PCs
- Cabos de rede RJ45
- Sistema Operacional: Linux (versão leve para PCs antigos, como Lubuntu / Linux Mint XFCE)
- Jogo: Urban Terror
- Software de controle: Timer Café (no servidor)

## 🖥️ Servidor
O servidor será o computador principal da lan house. Ele será responsável por:
- Hospedar a partida do Urban Terror
- Rodar o Timer Café para controlar o tempo de uso
- Mostrar quanto tempo cada PC tem restante
- Travar / liberar os computadores

**Funcionamento do Timer Café:**
1. O Timer Café é instalado no servidor (programa principal)
2. O cliente é instalado nos 8 PCs
3. Cada PC se conecta ao servidor pelo IP da rede local
4. No servidor, é possível ver todos os PCs, liberar tempo e acompanhar o uso
5. Quando o tempo acaba, o PC é bloqueado / deslogado automaticamente
6. Uso demonstrativo, sem cobrança real, apenas para controle de tempo da partida

## 🎮 Jogo Escolhido: Urban Terror
Escolhemos o Urban Terror porque:
- É leve e roda bem em PCs antigos
- É gratuito
- Tem modo multiplayer em rede local (LAN)
- Tem versão para Linux, sem precisar de emulador

## 💻 Como instalar o Urban Terror no Linux
1. Baixar a versão de Linux do Urban Terror no site oficial
2. Extrair o arquivo baixado
3. Dar permissão de execução no arquivo do jogo
4. Instalar as dependências que faltarem
5. Abrir o jogo e criar / entrar em uma partida em rede
6. No servidor: criar a partida
7. Nos outros PCs: entrar pelo IP do servidor

## 🌐 Rede / Topologia
Servidor (192.168.0.1) -> Switch -> PC 01 até PC 08

Todos os computadores estarão na mesma rede local, com IP fixo, para facilitar a conexão do jogo e do Timer Café.

## ⚠️ Dificuldades Encontradas e Como Resolvemos

### 1. PCs que às vezes não ligavam
Alguns computadores apresentavam falhas ao ligar, não davam vídeo ou desligavam sozinhos.

**O que fizemos:**
Testamos a fonte, limpamos a memória RAM e os contatos com borracha, trocamos os cabos de energia e verificamos as conexões internas. Depois da limpeza e dos testes, os PCs voltaram a ligar normalmente.

### 2. Dificuldade para instalar o Urban Terror no Linux
Por serem PCs antigos com Linux, tivemos dificuldade na instalação, pois o jogo não estava abrindo direto e faltavam algumas dependências / bibliotecas.

**O que fizemos:**
Baixamos a versão correta para Linux, extraímos os arquivos, demos permissão de execução e instalamos as dependências que faltavam. Depois disso, o jogo abriu e conseguimos testar a partida em rede.

## ✅ Resultado
Conseguimos montar a rede, instalar o Linux nos PCs, instalar o Urban Terror e testar o jogo em rede local com o controle de tempo pelo servidor, simulando o funcionamento de uma lan house real.

## 📚 Conclusão
Com este projeto, aprendemos a reaproveitar computadores antigos, configurar uma rede local, instalar e configurar Linux, resolver problemas de hardware e software e trabalhar em equipe para montar uma lan house funcional.

## 👥 Autores
- Rafaela
- Gabriela
- Millena 
- Gabriel 
- ⁠Jamile
