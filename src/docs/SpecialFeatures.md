# Special features

There are cases where we need some special things vuenut knows that and that's why we implemented some of them.

## Secure Vuenut

You need vuenut to have security so that not everyone can see the information of the store or if you are in production and do not want customers to see unnecessary information but you need to review the data for any bug or problem, vuenut understands you so just add a password let's see as.

```html
  <vuenut password="mypassword" :store="$store.state"/>
```
o puede ser una contraseña dinamica que viene del servidor o de una peticion externa

```html
<template lang="html">
  <div class="con-my-app">    
    <vuenut :password="myDynamicPassword" :store="$store.state"/>
  </div>
</template>
<script>
export default {
  data(){
    return {
      myDynamicPassword:"I'm a password"
    }
  }
}
</script>

<style lang="css">
</style>
```

## vuenut not visible

If the great project you are doing needs to be tested or reviewed for any problem or bug and that vuenut is seen by the end user, it is a problem you can hide it.
With adding the word `unseen` the problem is solved.

```html   
  <vuenut unseen :store="$store.state"/>
```

## New Great Functions

**Vuenut** is a library in progress that will continue to grow and implement new features, some are already in process in case you have a great idea or solution we would be delighted that you communicate it to our [Issues](https://github.com/lusaxweb/vuenut/issues) to improve or implement it together
