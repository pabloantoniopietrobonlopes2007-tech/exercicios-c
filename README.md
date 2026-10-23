# Exercícios em C

Coleção de exercícios de lógica e estruturas de dados resolvidos em C durante a
faculdade, o livro de estudos e plataformas de prática. **209 programas.**

## Conteúdo

| Pasta | O que tem | Arquivos `.c` |
|---|---|---|
| `codeBlocks/exercicios IFSP/` | Exercícios das aulas do IFSP | 123 |
| `codeBlocks/the huxley IFSP/` | Listas do juiz Huxley | 42 |
| `Beecrowd/` | Soluções de problemas do Beecrowd | 19 |
| `codeBlocks/Estudos Livro/` | Exercícios de livro (vetores, matrizes, structs) | 16 |
| `codeBlocks/Provas IFSP/` | Questões de provas anteriores | 4 |
| `codeBlocks/estudo solo/` | Testes próprios | 3 |
| `codeBlocks/OBI/` | Olimpíada Brasileira de Informática | 2 |
| `Anotações/` | Resumos de sintaxe e observações | — |

## Temas cobertos

Condicionais · laços · vetores · matrizes · strings · funções · structs ·
ponteiros

## Como compilar

Cada exercício tem seu próprio `main.c`. Não há projeto de IDE configurado, então
compile direto:

```bash
gcc caminho/para/main.c -o programa
./programa
```

Alguns exercícios usam `math.h` (`pow`, `sqrt`) e precisam de `-lm` no fim:

```bash
gcc Beecrowd/ArrayFill3_1178/main.c -o arrayfill -lm
```

## Observações

- As soluções do Beecrowd usam o número do problema no nome da pasta
- Os arquivos `.cbp`, `.layout` e `.depend` do Code::Blocks ficam fora do
  versionamento: são gerados pela IDE e não fazem parte do código
- Nenhum binário ou arquivo `.o` é versionado

## Próximos passos

- [ ] Tabela de problemas do Beecrowd com link e status
- [ ] `Makefile` para compilar e limpar de uma vez
