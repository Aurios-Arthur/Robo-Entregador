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
