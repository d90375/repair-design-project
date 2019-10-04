##I used the webpack packer for this project##


**First you must install all the dependencies** `yarn add webpack webpack-cli style-loader css-loader sass-loader node-sass extract-text-webpack-plugin@next html-webpack-plugin webpack-dev-server file-loader -D` **or** `npm i webpack webpack-cli style-loader css-loader sass-loader node-sass extract-text-webpack-plugin@next html-webpack-plugin webpack-dev-server file-loader -D`

- [ ] If you need to use developent mode enter `yarn dev` or `npm run dev`
- [ ] If you need to use watch developent mode enter `dev:watch` or `npm run dev:watch`
- [ ] If you need to use production mode enter `yarn build` or `npm run build`
- [x] If you need to use production dev-server-mode mode enter `yarn start` or `npm run start`

```
    "dev": "webpack --mode development",
    "dev:watch": "webpack --mode development --watch",
    "build": "webpack --mode production",
    "start": "webpack-dev-server --mode development --open"
```