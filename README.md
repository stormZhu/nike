## 参考

https://github.com/adrianhajdin/nike_landing_page

## setup

```bash
npm create vite@latest nike --template react
cd nike

npm install -D tailwindcss@3 postcss autoprefixer
npx tailwindcss init -p

在 src/index.css 中添加
@tailwind base;
@tailwind components;
@tailwind utilities;
```
