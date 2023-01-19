# WEB

## Dependencies to Install

#### postcss - automatiza tarefas dentro do css
#### tailwindcss - plugin do postcss
#### autoprefixer - add prefixo de brouser como --webkit

- npm i tailwindcss postcss autoprefixer -D
- npx tailwindcss init -p "sendo o -p para criar o arquivo do postcss se nao vite nao consegue entender o tailwindcss"


## extensões to install
- Tailwind CSS
- PostCSS

## Config to work tailwind
````
- into global.css file:

@tailwind base;
@tailwind utilities;
@tailwind components;

- into tailwind.conf.cjs

content: [
    './src/**/*.tsx',
    './index.html'
  ],
````
