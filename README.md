# ♟️ Chess Challenge: Rei em Xeque

## Descrição

Seu desafio é criar uma função que verifica se o **Rei branco (K)** está em **xeque** com base na posição das peças no tabuleiro.

## 🧠 Regras

- O tabuleiro é uma matriz 8x8.
- As peças estão representadas por letras:
  - `K` = Rei branco
  - `q` = Rainha preta
  - `r` = Torre preta
  - `b` = Bispo preto
  - `n` = Cavalo preto
  - `p` = Peão preto
  - `.` = Casa vazia

## 🧪 Exemplo

### Entrada:
```python
board = [
  [".", ".", ".", ".", ".", ".", ".", "."],
  [".", ".", ".", ".", ".", ".", ".", "."],
  [".", ".", ".", ".", ".", ".", ".", "."],
  [".", ".", ".", "q", ".", ".", ".", "."],
  [".", ".", ".", ".", "K", ".", ".", "."],
  [".", ".", ".", ".", ".", ".", ".", "."],
  [".", ".", ".", ".", ".", ".", ".", "."],
  [".", ".", ".", ".", ".", ".", ".", "."]
]
```

### Saída esperada:
```
True  # O rei está em xeque pela rainha
```

## ✅ Requisitos

- Criar a função `is_king_in_check(board)` que retorna `True` se o rei está em xeque, ou `False` caso contrário.

## 🚀 Entrega

- Faça um fork deste repositório
- Implemente a solução
- Envie o link com sua resposta final
