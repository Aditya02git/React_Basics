# React_Basics

vite.config.js:-

import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'

// https://vite.dev/config/
export default defineConfig({
  plugins: [react()],
  server: {
    open: true, //for automatic open browser (default chrome)
    port: 3001, //open in the port 3001
  }
})


# For custom command

package.json:-

"scripts": {
"dev": "vite" //npm run dev
"start": "vite --open" //npm start
"fuckoff": "vite" //npm run fuckoff
}
