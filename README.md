[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/zHqjFsRx)
# Diagnóstico de retomada - Teoria da Computação

Esta atividade serve para mapear o que você já domina sobre linguagens formais, autômatos, gramáticas e computabilidade.

Responda individualmente. Use suas palavras. Se usar IA depois da primeira tentativa, registre o uso na seção 7.

## 1. Mapa do que eu lembro

Marque cada tópico como: lembro bem, lembro parcialmente, não lembro, nunca vi ou não tenho certeza.

- alfabeto: lembro bem
- cadeia: lembro bem
- linguagem: lembro parcialmente
- gramática: lembro paarcialmente
- autômato finito: lembro bem
- linguagem regular: lembro bem
- linguagem livre de contexto: lembro parcialmente
- linguagem sensível ao contexto: lembro parcialmente
- linguagem irrestrita: lembro parcialmente
- hierarquia de Chomsky: não lembro
- computabilidade: lembro bem
- máquina de Turing: lembro bem

## 2. Definições com exemplo

Explique, com suas palavras e com um exemplo simples, usando o alfabeto `Sigma = {a, b}`.

1. O que é um alfabeto? o conjunto de tokens que o automato recebe
2. O que é uma cadeia? sequencia de simbolos
3. O que é uma linguagem? um conjunto de simbolos
4. O que é uma gramática? regras 

## 3. Linguagens

Considere as linguagens:

```text
L1 = { w em {0,1}* | w termina com 01 }
L2 = { a^n b^n | n >= 0 }
L3 = { a^n b^n c^n | n >= 0 }
```

Para cada linguagem:

1. escreva três palavras que pertencem à linguagem;
   L1:w, 0, 1 | L2:a, n, b | L3:a, n, c
2. escreva duas palavras que não pertencem;
   L1:j, q, r, | L2:k, l, f | L3:s, m, g
3. diga, se souber, em qual classe ela provavelmente se encaixa;
   nao sei se entendi o que "classe quer dizer"
4. explique o motivo em linguagem simples.
   não me recordo de estudar classe na disciplina
Não há problema em dizer "não sei". Nesse caso, escreva o que te deixou em dúvida.

## 4. Autômato finito

Considere o autômato abaixo, sobre o alfabeto `{0,1}`:

```text
Estados: q0, q1, q2
Estado inicial: q0
Estado final: q2

Transições:
q0 --0--> q1
q0 --1--> q0
q1 --0--> q1
q1 --1--> q2
q2 --0--> q1
q2 --1--> q0
```

Responda:

1. Qual linguagem esse autômato parece reconhecer?
   0 e 1
2. Execute manualmente as cadeias abaixo e diga se aceita ou rejeita:
   - `01` aceita e vai pra q2
   - `101` aceita e vai pra q2
   - `100` aceita e vai pra q1
   - `1101` aceita e vai pra q2
   - `111` permanece em q0
3. Monte uma tabela curta mostrando o caminho dos estados para pelo menos duas cadeias.
   `111`: `q0--1-->q0--1-->q0--1-->q0`
   `01`: `q0--0-->q1--1-->q2`
## 5. Gramática

Considere a gramática:

```text
S -> aS
S -> b
```

Responda:
não entendi
1. Gere cinco cadeias produzidas por essa gramática.
2. Descreva a linguagem em palavras.
3. Essa gramática parece regular, livre de contexto ou outra classe? Justifique de forma simples.

## 6. Ponto de dificuldade

Escolha um tópico da lista inicial e escreva:
   linguagem
1. o que você entende dele;
   linguagem é um conjunto de simbolos que forma um token para o automato
2. onde você se confunde;
   nao entendi totalmente o assunto, não sei bem como interpretar e trabalhar em cima dela
3. que tipo de explicação ajudaria: desenho, exemplo, exercício guiado, analogia, prova passo a passo ou lista curta.
   exemplo junto de um exercício já ajudaria bastante
## 7. Uso de IA, se houver
   não houve
Se você usou IA depois da primeira tentativa, registre:

```text
Pergunta feita:
Resumo da resposta:
Como eu verifiquei:
O que eu alterei na minha resposta:
O que ainda não entendi:
```

## Submissão no Moodle

Depois de finalizar, copie no Moodle:

```text
Repositório: https://github.com/frndchagas-org/diagn-stico-de-retomada-teoria-da-computa-o-arthuraguiar-del/tree/main
Commit final: Update README.md
Autoavaliação: nível atual: de 0 a 10, 7
maior dificuldade: gramatica
tópico que precisa ser retomado: hierarquia de Chomsky
```
