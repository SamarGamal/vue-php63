# vue-php63

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### Vue Sequence
1- Create file in folder views "Dummy.vue"
2- App.vue
    <router-link to="/dummy">dummy</router-link>
3- router => index.js
    import Dummy from '../views/Dummy.vue'

    , {
        path: '/dummy',
        name: "dummy",
        component: Dummy
    }
4- Create component in folder components "DummyComp.vue"
5- in view Dummy.vue
    <template>
        <Hello />
    </template>
    <script>
        import Hello from '@/components/DummyComp.vue'

        export default{
            components: {
                Hello
            }
        }
    </script>