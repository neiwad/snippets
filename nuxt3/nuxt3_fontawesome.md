# Nuxt3 + Fontawesome
## Dependencies
- @fortawesome/fontawesome-svg-core : ^1.2.36
- @fortawesome/free-brands-svg-icons : ^5.15.4
- @fortawesome/free-solid-svg-icons: ^5.15.4
- @fortawesome/vue-fontawesome : ^3.0.0-5
## Steps
### Add Fontawesome CSS to the Nuxt config
```
import { defineNuxtConfig } from ‘nuxt3’
export default defineNuxtConfig({
     css: [
        ‘@fortawesome/fontawesome-svg-core/styles.css’
    ],
})
```
### Create the plugin