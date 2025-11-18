# Trabalho de Computação Gráfica

**Aluno: Brenno Cezário de Oliveira Pereira**

**Matrícula: 202110035111**

## Compilar e executar código

`gcc main.c -lglut -lGL -lGLU -lm -o exe`

`./exe`

## Modelos utilizados
- Buda Feliz
- Coelho de Stanford
- Dragão Chinês
- Busto de Serápis

## Recursos necessários
1. **Sistema Operacional:** Linux (distribuições compatíveis com GCC e pacotes de desenvolvimento padrão).

2. **Bibliotecas de Desenvolvimento:**
- FreeGLUT (ou GLUT)
- OpenGL (-lGL)
- GLU (-lGLU)

## Observação

**Estrutura de Diretórios:**

1. Baixe os arquivos ZIP dos modelos no endereço: [https://casual-effects.com/data/index.html](https://casual-effects.com/data/index.html) .

2. Coloque os arquivos ZIP no mesmo diretório que o código-fonte (`main.c`).

3. Extraia todos os arquivos ZIP nesse diretório.

**Textura:**

Para os modelos que possuem parâmetros de textura (Coelho de Stanford), faça o download de um arquivo bitmap (BMP) e então coloque no mesmo diretório do código-fonte (`main.c`). Há um exemplo no repositório do github: [https://github.com/BrennoCezario/obj-viewer](https://github.com/BrennoCezario/obj-viewer)

**Importante:** O código espera que os arquivos do modelo e da textura estejam diretamente no mesmo diretório que o arquivo `main.c`.
