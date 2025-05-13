# Desenvolvimento Web Avançado com Vue (v2 e v3) e Vuex

[![Udemy](https://img.shields.io/badge/Udemy-Curso-green?logo=udemy)](https://www.udemy.com/course/desenvolvimento-web-avancado-com-vue-strapi-vuex-e-vuetify/?couponCode=CP130525BRGB)
[![Vue.js](https://img.shields.io/badge/Vue.js-3.x-brightgreen?logo=vue.js)](https://vuejs.org/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Este repositório reúne os projetos e exercícios realizados durante o curso **Desenvolvimento Web Avançado com Vue (v2 e v3) e Vuex**, ministrado pelo instrutor Jorge Sant Ana na Udemy.

---

## Sobre o Curso

O curso é focado no desenvolvimento de aplicações web modernas utilizando o framework **Vue.js** (versões 2 e 3), com ênfase em boas práticas, produtividade e ferramentas essenciais para o desenvolvimento profissional.

### Principais Aprendizados

- **Fundamentos do Vue.js:** Compreensão profunda das propriedades, diretivas, ciclo de vida dos componentes e data binding.
- **Vue CLI:** Configuração e utilização para iniciar projetos profissionais, incluindo plugins, variáveis de ambiente, ESLint e Webpack.
- **Componentes Reutilizáveis:** Criação de componentes Single File, uso de props, slots, eventos personalizados e mixins.
- **Gerenciamento de Estado com Vuex:** Centralização e controle do estado da aplicação para projetos complexos.
- **Roteamento com Vue Router:** Navegação entre componentes e gerenciamento de rotas.
- **Integração com Backend:** Uso do Strapi para criar APIs e JSON Server para simular backend.
- **Deploy e Versionamento:** Uso do Git, Bitbucket e deploy no Heroku.
- **Ferramentas Avançadas:** Vue Devtools para depuração, máscaras de input, diretivas customizadas e animações.
- **Extras:** Desenvolvimento de aplicações desktop com Vue 3 e Electron.

---

## Requisitos

Para acompanhar o curso, é importante ter conhecimentos básicos em:

- HTML
- CSS
- Bootstrap
- JavaScript

---

## Exemplo Simples de Código Vue

```vue
<template>
  <div>
    <h1>{{ mensagem }}</h1>
    <button @click="alterarMensagem">Clique aqui</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      mensagem: 'Olá, Vue!'
    }
  },
  methods: {
    alterarMensagem() {
      this.mensagem = 'Você clicou no botão!'
    }
  }
}
</script>

<style scoped>
h1 {
  color: #42b983;
}
button {
  padding: 8px 16px;
  background-color: #35495e;
  color: white;
  border: none;
  cursor: pointer;
}
button:hover {
  background-color: #42b983;
}
</style>
```
Como ficou o visual do código acima

<div align="center">
<img src="Aulas\1_Iniciando_com_VueJS/Arquivos/Imagem_do_codigo.png" alt="Iamgem do Front do codigo do README" width="400" style="border:2px solid #000; border-radius:8px;">
</div>
---

## Sobre o Instrutor

Jorge Sant Ana é tecnólogo em Informática para Gestão de Negócios e pós-graduado em Gestão de Projetos de TI. Com ampla experiência em diversas tecnologias, ele é um entusiasta do desenvolvimento de software e educador dedicado.

---

## Objetivo deste Repositório

Este repositório tem como objetivo armazenar e organizar todo o conteúdo prático desenvolvido durante o curso, servindo como referência para estudos futuros e para demonstrar a evolução no desenvolvimento com Vue.js.

---

## Contato

- LinkedIn: [https://www.linkedin.com/in/jorge-sant-ana/](https://www.linkedin.com/in/jorge-sant-ana/)
- Udemy: [Curso no Udemy](https://www.udemy.com/course/desenvolvimento-web-avancado-com-vue-strapi-vuex-e-vuetify/?couponCode=CP130525BRGB)

---

## Agradecimentos

Agradeço ao instrutor Jorge Sant Ana pela excelente didática e conteúdo de qualidade que tem me ajudado a avançar no desenvolvimento web com Vue.js.

---

> **Licença:** Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.