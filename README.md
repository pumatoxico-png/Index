# 🐍 Inserção e Remoção de Elementos em Listas

> Exercício de Python sobre manipulação de elementos em listas.

## 🎯 Objetivo
Praticar diferentes métodos para adicionar, inserir, remover, excluir e localizar elementos em uma lista.

## 📚 Conceitos utilizados
- Listas (`[]`)
- `append()` — adiciona um elemento ao final.
- `insert()` — insere um elemento em uma posição específica.
- `remove()` — remove um elemento pelo valor.
- `pop()` — remove e retorna um elemento.
- `del` — exclui um elemento pela posição.
- `in` — verifica se um elemento existe.
- `index()` — retorna a posição de um elemento.

## ⚙️ Código

```python
sensores = ['T01', 'T02']

sensores.append('T03')
sensores.insert(0, 'T00')
sensores.remove('T02')

ultimo = sensores.pop()

del sensores[0]

'T01' in sensores
sensores.index('T01')
```

## 📊 Funcionamento

1. Cria uma lista com dois sensores.
2. Adiciona `T03` ao final com `append()`.
3. Insere `T00` na primeira posição com `insert()`.
4. Remove `T02` utilizando `remove()`.
5. Remove o último elemento com `pop()` e armazena seu valor em `ultimo`.
6. Exclui o primeiro elemento utilizando `del`.
7. Verifica a existência de `T01` com `in`.
8. Consulta a posição de `T01` com `index()`.

## 💻 Resultado final

```text
Lista: ['T01']
Último removido: T03
'T01' in sensores: True
sensores.index('T01'): 0
```

## 🧠 Aprendizado
Compreensão dos principais métodos de manipulação de listas em Python, diferenciando as formas de inserção, remoção, exclusão e localização de elementos.
