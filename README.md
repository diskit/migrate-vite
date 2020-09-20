# migrate-vite

This repository is intended for migration from `vue-cli` to `vite`

## flow

1. create project by vue-cli  
ts + vue3 + jest + prettier
1. remove `vue-cli`  
remove from package.json by manually.  
    - @vue/*
    - core-js
1. add `vite`  
`yarn add -D vite jest ts-jest`
1. modify scripts in package.json
1. move public/index.html to root
1. modify jest.config.js  
remove preset. add roots, testMatch. modify transform
1. remove webpack placeholder from index.html