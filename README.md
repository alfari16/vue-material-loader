# Vue-Material-Loader-Component

a VueJS single component to make a litle, nice and simple material loader

### Prerequisites

Just import it as simple as another component you've made

```
<script>
    import loader from 'vue-material-loader'
    export default {
        components:{loader},
    }
</script>    
```

Now you can call it in the template section and style it!
```
<!-- There are 3 props defined. It's value mention below is the default value. you can custom it as much as you want -->
<template>
    <loader
        :color="'#3f51b5'"
        :size="'65'"
        :stroke-width="'6'"
    ></loader>
<template>
```
```
Note: The maximum value _stroke-width_ prop is 6. Depend on the best material loader look like
```
### Installing

```
npm install vue-material-loader
```

You've done! Go make a great stuff!