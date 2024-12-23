# vite + vue3 + Electron

## 1. 设置 vite 端口号: vite.config.js

    import { defineConfig } from 'vite'
    import vue from '@vitejs/plugin-vue'

    // https://vitejs.dev/config/
    export default defineConfig({
    plugins: [vue()],
    base: './',
    server: { port: 2000 }
    })
