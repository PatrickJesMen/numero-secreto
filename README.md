# 🎮 Jogo do Número Secreto

<p align="center">
  <img src="https://img.shields.io/static/v1?label=Linguagem&message=JavaScript&color=F7DF1E&style=for-the-badge&logo=javascript" alt="JavaScript">
  <img src="https://img.shields.io/static/v1?label=Framework&message=ResponsiveVoice&color=green&style=for-the-badge" alt="ResponsiveVoice">
</p>

> Uma experiência interativa onde o desafio é descobrir o número oculto, com acessibilidade via narração de voz.

---

## 📸 Demonstração

<div align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNHJndXFmN3R3eXN5eXN5eXN5eXN5eXN5eXN5eXN5eXN5JmVwPXYxX2ludGVybmFsX2dpZl9ieV9pZCAmY3Q9Zw/3o7TKVUn7iM8FMEU24/giphy.gif" width="600px" alt="Preview do Jogo">
</div>

## 🚀 Funcionalidades

- **Lógica de Sorteio**: O sistema gera um número aleatório e garante que ele não se repita até que todos os números possíveis sejam sorteados.
- **Feedback Visual**: Mensagens dinâmicas que orientam se o número secreto é maior ou menor que o chute.
- **Acessibilidade (Screen Reader)**: Integração com a API `ResponsiveVoice` para leitura dos textos em português brasileiro.
- **Design Responsivo**: Interface adaptável para diferentes tamanhos de tela.
- **Sistema de Reinicialização**: Botão que reseta o estado do jogo sem necessidade de recarregar a página.

## 🛠️ Tecnologias Utilizadas

As seguintes ferramentas foram utilizadas na construção do projeto:

- [HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS) (Flexbox, Gradientes e Media Queries)
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) (Manipulação de DOM e Lógica)
- [ResponsiveVoice.js](https://responsivevoice.org/) (Sintetizador de voz)

## 🎮 Como Jogar

1. Digite um número no campo de entrada.
2. Clique em **"Chutar"**.
3. O jogo dirá se você acertou ou se o número secreto é maior/menor.
4. Ao acertar, o botão **"Novo jogo"** será habilitado para você começar uma nova rodada.

---

## 💻 Como rodar o projeto

```bash
# Clone este repositório
$ git clone [https://github.com/SEU_USUARIO/nome-do-repositorio.git](https://github.com/SEU_USUARIO/nome-do-repositorio.git)

# Acesse a pasta do projeto
$ cd nome-do-repositorio

# Abra o arquivo index.html no seu navegador de preferência.
