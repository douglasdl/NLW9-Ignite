# NLW9-Ignite
NLW9 - Ignite

## Server
Check installed Node.js version:
```sh
nvm ls
```

Use Node LTS:
```sh
nvm 16.17
```

Create the project:
```sh
npm init -y
```
Install dependencies:
```sh
npm install express
npm install cors
npm install @prisma/client
```

Install development dependencies:
```sh
npm install typescript -D
npm install @types/express -D
npm install @types/cors -D
npm install ts-node-dev -D
npm install prisma -D
npx prisma init
npx prisma init -h
npx prisma init --datasource-provider SQLite
npx prisma migrate dev
npx prisma studio
npm install zod
```

Create the tsconfig.json file:
```sh
npx tsc --init
```

## Web
Create the project:
```sh
npm create vite@latest
```

Install dependencies:
```sh
npm install phosphor-react
```

Install development dependencies:
```sh
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

## Mobile
- Node, Git, Watchman --> Expo CLI

Install Expo CLI:
```sh
npm install --global expo-cli
```

Create the project (blank - Typescript):
```sh
expo init mobile
```

Start the project:
```sh
expo start
```

Install Expo dependencies
```sh
expo install expo-font @expo-google-fonts/inter
expo install react-native-safe-area-context
expo install expo-linear-gradient
```


## Tools
 - [Insomnia](https://insomnia.rest/download)
 - [Postman](https://www.postman.com/)
 - [Hoppscotch](https://hoppscotch.io/pt-br)

 - [Tailwind](https://tailwindcss.com/)

 - [Expo Google Fonts](https://docs.expo.dev/guides/using-custom-fonts/)
 - [React Navigation](https://reactnavigation.org/)

 - [Figma](https://www.figma.com/file/mAhMMRTiieN3gGtl0fGv6i/NLW-eSports)
 - [Notes](https://efficient-sloth-d85.notion.site/Ignite-18c1174738e54f1d8e742f794e210cd2)

 - [Zod](https://github.com/colinhacks/zod) - Data validation.

## Database
### Abstraction Level 1 - Pure SQL Query
 - [SQLite](https://github.com/TryGhost/node-sqlite3) ```sh npm install sqlite3```

### Abstraction Level 2 - Query Builder
 - [Knex.js](https://knexjs.org/)

### Abstraction Level 3 - ORM (Object Relational Mapper)
 - [Sequelize](https://sequelize.org/)
 - [Type ORM](https://typeorm.io/)
 - [Prisma](https://www.prisma.io/)

## Extensões
- [PostCSS Language Support](https://marketplace.visualstudio.com/items?itemName=csstools.postcss)
- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
- [R Component](https://marketplace.visualstudio.com/items?itemName=rodrigorgtic.rcomponent)
- [Prisma](https://marketplace.visualstudio.com/items?itemName=Prisma.prisma)
- [SQLite](https://marketplace.visualstudio.com/items?itemName=alexcvzz.vscode-sqlite)