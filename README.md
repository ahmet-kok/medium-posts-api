<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=128px src="assets/icon.png" alt="Project logo"></a>
</p>

<h3 align="center">Medium Posts API</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]() [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> Unofficial Medium API that returns the JSON of your posts
    <br> 
</p>

## 📝 Table of Contents

- [How to use](#how_to_use)
- [Deployment](#how_to_contribute)
- [Built Using](#built_using)
- [Authors](#authors)


## 🏁 <span id="how_to_use">How to use </span>

Do a GET request for the url together with your Medium user

```bash
https://mediumpostsapi.herokuapp.com/?usermedium=@yourmediumusername
```

For example the request for the url below...

```bash
https://mediumpostsapi.herokuapp.com/?usermedium=@davidfernandodamata21
```
...will returns the following result

```bash
[
  {	
  title: "Como reduzir a quantidade de IFs"
  link: "https://medium.com/david-fernando/como-reduzir-a-quantidade-de-ifs-4484fc728397?source=rss-e1120fb0abef------2"
  image: "https://cdn-images-1.medium.com/max/1024/1*6wlQhci1Pot4BWUPDpHbfw.jpeg"
  description: "Uma introdução ao design pattern Strategy com JavaScript. Se você achou esse artigo em sua…"
  },
  {
  title: "Por que usar TypeScript?"
  link: "https://medium.com/david-fernando/por-que-usar-typescript-ca15607eed33?source=rss-e1120fb0abef------2"
  image: "https://cdn-images-1.medium.com/max/1024/1*ODf4X51nKEMElimXA706gQ.jpeg"
  description: "Veja quais são os benefícios de utiliza-lo em seus projetos. O TypeScript realmente pode n…"
  }
]
```

### <span id="how_to_contribute">How to contribute</span>

 Fork this repository, make clone for your machine, and coding!

 To run the development server use one of the commands below

```bash
yarn dev

# or

npm dev
```
When everything is ready, do a pull request to the branch development.

## ⛏️ <span id="#built_using">Built Using</span>

- [Express](https://expressjs.com/) - Server Framework
- [NodeJs](https://nodejs.org/en/) - Server Environment

## ✍️ <span id="#authors">Author</span>

- [@david-fernando](https://github.com/david-fernando) - Idea & Initial work
