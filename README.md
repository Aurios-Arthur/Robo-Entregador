# 🤖 Desafio Robô Entregador — direto do Eloquent JavaScript

Fala, dev! 👋

Vi esse desafio no livro **Eloquent JavaScript** e achei incrível para treinar lógica, modelagem de sistemas e raciocínio funcional.

Então resolvi trazer ele traduzido, adaptado e aberto aqui pra galera resolver 🚀  
**Sem solução, sem spoiler! Só o problema.** Bora encarar?

---

## 📦 O Desafio

Você precisa programar um **robô entregador de pacotes** em uma vila chamada Meadowfield.

A vila é composta por **11 locais** e **14 estradas** conectando esses locais. Pacotes aparecem em locais aleatórios e têm um endereço de destino.

O robô precisa se mover pela vila, pegando e entregando os pacotes corretamente.

---

## 🌐 Mapa da Vila

A vila é representada por essas estradas:

![Mapa da Vila](./db3d60cf-b714-4eda-9d10-50295fbdff57.jfif)
```js
const roads = [
  "Alice's House-Bob's House", "Alice's House-Cabin",
  "Alice's House-Post Office", "Bob's House-Town Hall",
  "Daria's House-Ernie's House", "Daria's House-Town Hall",
  "Ernie's House-Grete's House", "Grete's House-Farm",
  "Grete's House-Shop", "Marketplace-Farm",
  "Marketplace-Post Office", "Marketplace-Shop",
  "Marketplace-Town Hall", "Shop-Town Hall"
];
```

## 🎯 Regras do Jogo

 - O robô começa em um local aleatório.

 - Existem vários pacotes espalhados pela vila. Cada um tem:

   - Um local atual (onde está)

   - Um destino (onde precisa ser entregue)

 - Em cada turno, o robô pode:

   - Se mover para um local conectado

   - Pegar qualquer pacote que esteja no local atual

   - Entregar qualquer pacote cujo destino seja o local atual

   - O desafio termina quando todos os pacotes forem entregues.

## 🔍 Objetivo

 - Programe a simulação do robô de forma que:

   - Ele consiga se mover pela vila com base nas conexões

   - Ele pegue e entregue os pacotes corretamente

   - A cada turno, a "realidade" (estado da vila) seja atualizada

Bônus: pense em como fazer o robô tomar decisões melhores (mais eficientes).

## 🧠 O que você vai treinar

 - Modelagem de estado

 - Imutabilidade de dados

 - Grafos

 - Simulações

 - Pensamento funcional (ou POO, se quiser testar as diferenças)

## 🛠️ Comece assim

Monte um objeto que represente o estado da vila. Por exemplo
```js
  let estado = {
  localDoRobo: "Post Office",
  pacotes: [
    { lugar: "Post Office", destino: "Alice's House" },
    { lugar: "Daria's House", destino: "Shop" }
  ]
};
```
A ideia é: a cada movimento do robô, você atualiza esse estado (ou cria um novo).

---

## 📘 Fonte
Inspirado no capítulo "A Robot" do livro Eloquent JavaScript por Marijn Haverbeke.

---

📣 Quer compartilhar sua solução?
Crie um repositório com a sua versão

Me marca no LinkedIn 

Ou comenta aqui no repositório e bora trocar ideia 😎
