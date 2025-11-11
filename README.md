# Trabalho de Computação Gráfica

**Aluno: Brenno Cezário de Oliveira Pereira**
**Matrícula: 202110035111**

## Construir executável

**Compilar arquivo:**
`gcc main.c -o exe -lglut -lGL -lGLU`

**Executar arquivo gerado:**
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

3. Fazer download dos modelos utilizados no endereço: https://casual-effects.com/data/index.html 

## Observação

**Estrutura de Diretórios:**

1. Baixe os arquivos ZIP dos modelos.

2. Coloque os arquivos ZIP no mesmo diretório que o seu código-fonte (`main.c`).

3. Extraia todos os arquivos ZIP nesse diretório.

**Importante:** O código espera que as pastas dos modelos (ex: `bunny`, que contém `bunny.obj`) estejam diretamente no mesmo diretório que o arquivo `main.c`.