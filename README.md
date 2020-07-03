# twitter-explore-scaffold

Twitter explore page scaffold with sass for GTB project

![Mockup](mockup/twitter-explore.png)

## Install dependencies

```
yarn install
```

If you use npm,

```
npm install
```

## Start server

```
yarn start
```

If you use npm,

```
npm start
```

## JS and SCSS code lint in src/

```
yarn run lint
```

If you use npm,

```
npm run lint
```

## Format JS and SCSS files in src/

```
yarn run format
```

If you use npm,

```
npm run format
```

## NOTE

Your committed code will be automatically format and check lint when submit

1. 80%还原原型，button没有hover的状态，点击的时候会有focus的边框，建议可以加上hover样式以及去除outline
2. 有运用到所学的大部分知识，包括变量、mixins以及web 语义化
3. 页面整体比例有些失调
4. button_primary的mixin可以放入mixins中统一进行管理，并且button_primary这个mixin的名字也不是很通用，因为除了primary button之外，可能还会存在其他类型的button，建议换一个比较通用的名字，backgroud存在typo错误
5. label以及input可以作为一个整体，建议使用一个父级元素进行包裹，便于复用，同时也更加符合语义化；此外，content中的两个button也可以作为一个整体
6. index.html中line 24以及26行中的input标签建议自闭合 <input type="text" />
7. 尽量不要使用通配符 *，可能会导致页面中的一些不必要的元素进行原生样式的重写覆盖
