# Tarefa 33 — Página pessoal com DaisyUI

## Sobre o projeto

Esta página pessoal foi desenvolvida para a Tarefa 33 do módulo de Design Web do IFRN.

O projeto apresenta meu perfil como estudante de Informática para Internet, com interesse em **desenvolvimento Front-end e UI Design**.

A estrutura foi construída utilizando **DaisyUI sobre o Tailwind CSS**, combinando componentes prontos da biblioteca com classes utilitárias do Tailwind para criar um layout responsivo.

---

# Componentes DaisyUI utilizados

## Navbar

A `navbar` foi utilizada no cabeçalho da página.

Ela contém:

* Meu nome;
* Link para a seção Sobre;
* Link para Projetos;
* Botão de Contato.

Escolhi a `navbar` porque ela permite organizar a navegação principal de forma simples e facilita o acesso às diferentes partes da página.

---

## Hero

O componente `hero` foi utilizado logo depois do cabeçalho.

Ele apresenta:

* Meu nome;
* Minha área de interesse;
* Badges de Front-end Developer e UI Designer;
* Uma breve apresentação;
* Botões para acessar outras seções.

O `hero` foi escolhido porque é adequado para criar uma apresentação inicial com destaque visual.

---

## Badge

Os componentes `badge` foram utilizados para destacar habilidades, tecnologias e categorias.

Algumas das variações utilizadas são:

* `badge-primary`;
* `badge-secondary`;
* `badge-accent`;
* `badge-outline`.

Eles aparecem nas seções de apresentação e projetos.

---

## Card

Foram utilizados pelo menos três cards completos na seção de projetos.

Os projetos apresentados são:

1. **StudyTrack**
2. **Info-Web**
3. **Luffy Vendas**

Cada card utiliza a estrutura:

```html
<div class="card">
    <div class="card-body">
        ...
    </div>
</div>
```

Também foram utilizados cards adicionais na seção "Como desenvolvo meus projetos".

---

## Button

Foram utilizados diferentes estilos de botões DaisyUI.

Entre eles:

* `btn-primary`;
* `btn-secondary`;
* `btn-accent`;
* `btn-outline`;
* `btn-ghost`.

Os botões são utilizados para navegação, acesso aos projetos, contato e alteração do tema.

---

## Input

O formulário de contato utiliza os componentes `input` do DaisyUI.

Foram adicionados campos para:

* Nome;
* E-mail.

Também foi utilizado o componente `textarea` para a mensagem.

---

## Footer

O componente `footer` foi utilizado no final da página para apresentar o nome, a área de atuação e as tecnologias utilizadas no desenvolvimento.

---

# Justificativa das escolhas

## Navbar + Hero

Escolhi combinar `navbar` e `hero`.

A `navbar` organiza a navegação principal, enquanto o `hero` funciona como uma apresentação inicial mais destacada.

Essa combinação permite separar a função de navegação da apresentação do perfil.

## Cards

Escolhi utilizar `card` para os projetos porque cada projeto possui informações próprias.

O card permite organizar:

* Nome do projeto;
* Categoria;
* Descrição;
* Tecnologias;
* Botão de ação.

Dessa forma, os projetos ficam visualmente separados e fáceis de comparar.

## Badges

Os badges foram utilizados para representar tecnologias e categorias de forma rápida.

Eles ocupam pouco espaço e permitem identificar as principais características de cada projeto.

---

# Uso do Tailwind CSS

O DaisyUI fornece os componentes principais, mas algumas classes do Tailwind foram utilizadas para complementar o layout.

## Responsividade

Foram utilizadas classes como:

```text
sm:flex
md:grid-cols-2
lg:grid-cols-3
```

Essas classes permitem adaptar o layout para diferentes tamanhos de tela.

A seção de projetos, por exemplo, utiliza:

```html
<div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
```

Assim, a quantidade de colunas muda de acordo com o tamanho da tela.

## Espaçamento

Também foram utilizadas classes como:

```text
px-6
py-20
gap-6
max-w-6xl
mx-auto
```

Essas classes foram utilizadas para controlar espaçamento, largura e posicionamento dos elementos.

---

# Temas

A página utiliza o atributo:

```html
<html lang="pt-BR" data-theme="corporate">
```

Foram utilizados dois temas:

* `corporate`
* `business`

A página possui dois botões que permitem testar os temas diretamente no navegador.

```javascript
document.documentElement.setAttribute('data-theme', 'corporate')
```

e:

```javascript
document.documentElement.setAttribute('data-theme', 'business')
```

## Reflexão sobre os temas

O tema **corporate** ficou mais coerente com a proposta da página porque apresenta uma aparência adequada para um portfólio profissional.

O tema **business** também funciona corretamente e demonstra como os componentes DaisyUI podem mudar sua aparência sem precisar alterar individualmente as cores dos componentes.

---

# Responsividade

A página foi desenvolvida para funcionar em:

* Celulares;
* Tablets;
* Desktops.

O Tailwind foi utilizado para adaptar grids, espaçamentos e elementos de navegação conforme a largura da tela.

Os cards dos projetos, por exemplo, passam de uma organização vertical em telas pequenas para duas ou três colunas em telas maiores.

---

# Tecnologias utilizadas

* HTML5
* Tailwind CSS
* DaisyUI
* Git
* GitHub

---

# Branch

```text
feat/daisyui-tarefa33
```

---

# Autor

**Vitor Gabriel**

Estudante de Informática para Internet
Front-end Developer & UI Designer em formação.

Projeto desenvolvido para a disciplina de Design Web — IFRN.
