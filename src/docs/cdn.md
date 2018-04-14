# Quick-start CDN

**Vuenut** is a component created for all the developers of vuejs that we **love the simplicity** to implement vuenut in a simple frame you can add the cdn and ready vuenut does the magic.

<p class="tip"> **Vuenut** is a component based on [Vuejs](https://vuejs.org/) please before implementing it make sure that this our beloved vue in your big project.</p>


## Implementation by CDN

```html
<!DOCTYPE html>
<title>vuenut demo</title>
<script src="https://unpkg.com/vue"></script>
<script src="https://unpkg.com/vuenut/dist/vuenut.umd.js"></script>
<link rel="stylesheet" href="https://unpkg.com/vuenut/dist/vuenut.css">

<div id="app">
  <vuenut :store="store"/>
</div>

<script>
// test store
var store = {
  vuenut: 'Hello World'
}

new Vue({
  data(){
    return {
      store:store
    }
  }
}).$mount('#app')
</script>
```

## Example Run

We are sure that you would love to see vuenut Operated so you can play with it and review its features and charms.
[Codepen](https://codepen.io/lusaxweb/pen/dmLEKv)

## Detailed explanation of implementation

Sometimes there are complications or misunderstandings when we add a library or framework for the first time so because we do not review in detail the steps in case something happened to us

<p class="tip">If you are familiar with the libraries terms and components of vuejs you can skip this little tutorial</p>



- ### 1) Add Vuejs

First of all we have to add vue js so that everything can work perfectly
for this we add the line of code

```html
<script src="https://unpkg.com/vue"></script>
```

- ### 2) add Vuenutjs

After having incorporated vuejs we added the library so that we can implement the component

```html
<script src="https://unpkg.com/vuenut/dist/vuenut.umd.js"></script>
```

- ### 3) add Vuenut.css

We are ready with the js files but still one of the most important things our css styles that add the bellesa to our applications

```html
<link rel="stylesheet" href="https://unpkg.com/vuenut/dist/vuenut.css">
```

- ### 4) implement vuenut

All the external files are already added the most difficult is ready now let's pay attention on how to add vuenut to our great project

- To implement vuenut we first add the vuenut tag with the parameter: store which is where we put the application store, in this case it is just a test variable if you want to learn more about ** vuex ** you can check the [Official documentation]( https://vuex.vuejs.org/en/)

```html
<div id="app">
  <vuenut :store="store"/>
</div>

<script>
// test store
var store = {
  vuenut: 'Hello World'
}

new Vue({
  data(){
    return {
      store:store
    }
  }
}).$mount('#app')
</script>
```



## CDN URLs

- https://unpkg.com/vuenut/dist/vuenut.umd.js
- https://unpkg.com/vuenut/dist/vuenut.css
