# Maze Clicker

## Membros do Projeto
- **João Miguel Freitas** - [joaomiguelfreitas](https://github.com/joaomiguelfreitas)

## Disciplina
Programação Imperativa e Funcional - 2024.2

## Instituição de Ensino
CESAR School

## Descrição do Jogo
Maze Clicker é um jogo inspirado no clássico jogo da cobrinha. Nele, o jogador controla uma cobrinha que se move em um labirinto, coletando itens e evitando obstáculos. O objetivo é conseguir a maior pontuação possível ao coletar os itens que aparecem aleatoriamente no cenário.

### Regras do Jogo
- A cobrinha se movimenta continuamente em uma direção e o jogador pode mudar sua direção clicando nas setas (ou utilizando as teclas direcionais).
- Cada item coletado aumenta o tamanho da cobrinha e a pontuação do jogador.
- O jogo termina se a cobrinha colidir com as paredes do labirinto ou com ela mesma.
- O jogo pode ser reiniciado após a sua finalização.

## Instruções para Compilar e Executar
1. **Clone o repositório**
   ```bash
   git clone https://github.com/joaomiguelfreitas/maze-clicker.git
   cd maze-clicker
   ```

2. **Instale as dependências**
   Certifique-se de que você tem o [Node.js](https://nodejs.org/) instalado. Depois, instale as dependências necessárias:
   ```bash
   npm install
   ```

3. **Compile o projeto**
   Para compilar o projeto, utilize o seguinte comando:
   ```bash
   npm run build
   ```

4. **Execute o jogo**
   Para rodar o jogo, use:
   ```bash
   npm start
   ```

5. **Acesse o jogo**
   Abra o seu navegador e acesse `http://localhost:3000` para começar a jogar.

## Contribuições
Sinta-se à vontade para contribuir com o projeto, abrir issues ou enviar pull requests!

---

Divirta-se jogando Maze Clicker! 🎮

# cli-lib
Command Line Interface library, for developing CLI applications and games in C. It has functions to access keyboard, screen and manage timing tasks.

## Requirements
- This library works with the follwing OS:
   - Linux based (Ubuntu, etc)
   - MacOS
- It is necessary to have GCC installed.

## Usage 
The file `main.c` has an example of how to use the Keyboard, Screen nd Timer functions. 

To build this example via command line, just switch to library root directory and type the following command:
```
$ gcc ./src/*.c -I./include -o cli-lib-example
```

To use this library to create your own apps, simply add source and header files to your project and compile it together with your own code, 
replacing the main.c file to your own.

