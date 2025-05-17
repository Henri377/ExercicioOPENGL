# Exemplo OpenGL: Triângulos com Cores Variadas

Este projeto demonstra como criar triângulos coloridos em uma janela OpenGL utilizando GLFW, GLEW e GLM. A cada clique do mouse, um novo vértice é adicionado. A cada três vértices, um triângulo é desenhado com uma cor diferente.

Este código foi baseado no **exemplo_02 fornecido em aula**.

## Como funciona

- Clique com o botão esquerdo do mouse para adicionar um vértice.
- A cada três cliques, um triângulo é formado.
- Cada triângulo recebe uma cor diferente, alternando entre várias cores predefinidas.
- A janela utiliza projeção ortográfica, onde cada unidade corresponde a um pixel.

## Requisitos

- GLFW
- GLEW
- GLM
- OpenGL 3.2+

## Compilação (exemplo no Windows)

```sh
g++ exemplo_02.cpp -o exemplo_02 -lglew32 -lglfw3 -lopengl32
```

## Execução

Basta rodar o executável gerado:

```sh
./exemplo_02
```

## Controles

- **Clique esquerdo:** adiciona um vértice na posição do mouse.
- **ESC:** fecha a janela.
