<p align="center">
  <a href="https://github.com/medistream-team/vue2-fullpage-modal" target="_blank">
    <img width="150px" src="vue2-fullpage-modal.svg" />
  </a>
</p>
<p align="center">
  <a href="https://github.com/medistream-team/vue2-fullpage-modal" target="_blank">
    <img width="320px" src="vue2-fullpage-modal-label.png" />
  </a>
</p>
<p align="center">
  <img alt="Version" src="https://img.shields.io/npm/v/vue2-fullpage-modal?color=blue" />
  <a href="#" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://vuejs.org/" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/vue-2.x-brightgreen.svg" />
  </a>
</p>

<p align="center">
  <img width="250px" src="example-scroll.gif" />
</p>


## Documentation

Checkout [Documentation📝](https://medistream-team.github.io/vue2-fullpage-modal/)

## Install

```sh
npm install vue2-fullpage-modal
```

## Usage

### Plugin

```javascript
import FullpageModal from 'vue2-fullpage-modal'

Vue.use(FullpageModal)
```

### Component

```html
<template>
  <div>
    <img @click="openModal" src="/logo.png" >
  </div>
</template>
<script>
import HelloWorld from './HelloWorld'

export default {
// ...
  methods: {
    openModal() {
      this.$FModal.show(
        { component: HelloWorld },
        { msg: "Welcome to Your Vue.js App" }
      )
    }
  }
}
</script>
```

## Contributor

#### 👥  [**Medistream**](https://github.com/medistream-team) 

  - [ktseo41](https://github.com/ktseo41) <br />
  - [gliburch](https://github.com/gliburch)

## 📝 License

Copyright © 2021 [Medistream](https://github.com/medistream-team)<br />
This project is [MIT](https://github.com/medistream-team/vue2-fullpage-modal/blob/master/LICENSE) licensed.


<!-- ***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_ -->