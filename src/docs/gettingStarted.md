# Getting Started

Vuenut is a library that you can use in a complex project without any problem to install the dependency you just have to execute the commands.

## Install en Proyecto NPM / YARN
``` bash
# npm
npm install vuenut

# yarn
yarn add vuenut
```

## Use

To use vuenut you must import the plugin and use the functionality of vuejs to add plugins `Vue.use ()` only with implementing these lines of code and you only need to add to vuenut where best fits your needs

```javascript
import Vue from 'vue'
import Vuenut from 'vuenut'

import 'vuenut/dist/vuenut.css'
Vue.use(Vuenut)
```

## Implement vuenut

 To implement vuenut we first add the vuenut tag with the parameter: store which is where we put the application store, if you want to learn more about ** vuex ** you can check the [Official documentation]( https://vuex.vuejs.org/en/)

<p class="tip">important when adding the store put `$store.state` with the included **state** so that vuenut can work without problem.</p>

```html
<template lang="html">
  <div class="con-my-app">    
    <vuenut :store="$store.state"/>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="css">
</style>
```
