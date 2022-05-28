## React18 Vite Storybook Jest Styled-Components

### Create the project
npm create vite@latest vite-react-boilerplate -- --template react

### Install dependencies
npm i

### Execute
npm run dev

### Install Prettier and ESLint
npm i eslint @babel/eslint-parser prettier eslint-config-prettier eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks eslint-plugin-storybook -D

### Install Jest
npm i jest @types/jest @babel/core @babel/eslint-parser @babel/preset-env @babel/preset-react babel-jest babel-loader jest-styled-components jest-environment-jsdom @testing-library/react @testing-library/jest-dom -D

### Styled-components
npm i styled-components && npm i -D @types/styled-components

### Config ESlint e o Prettier
create files: .eslintrc.js .prettierrc.js .editorconfig

### Config Styled-Components, GlobalStyles e ThemeProvider
npm i prop-types

### Config storybook
npx sb init

npm i -D html-webpack-plugin

npm run storybook
