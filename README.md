# app1

```
vue create app1 (default babel/eslint)
vue add @vue/pwa (manually add public/manifest.json)
```

```

https://naturaily.com/blog/pwa-vue-cli-3

{
  "name": "pwa",
  "short_name": "pwa",
  "icons": [
    {
      "src": "/img/icons/android-chrome-192x192.png",
      "sizes": "192x192",
      "type": "image/png"
    },
    {
      "src": "/img/icons/android-chrome-512x512.png",
      "sizes": "512x512",
      "type": "image/png"
    }
  ],
  "start_url": "/index.html",
  "display": "standalone",
  "background_color": "#000000",
  "theme_color": "#4DBA87"
}
```

## Vuetify
vue add vuetify

## mongodb - for vercel api/
npm install --save mongodb
npm install --save url
(sets up package.json for vercel to read)

npm install --save bcrypt



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
