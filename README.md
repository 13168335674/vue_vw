**快速开始：**
* 初始化vue项目
```
vue create vw_demo 
```
* 安装依赖
`
yarn add postcss-aspect-ratio-mini postcss-px-to-viewport postcss-write-svg postcss-cssnext postcss-viewport-units cssnano cssnano-preset-advanced --dev 
`
* 配置postcssconfig.js
```"postcss-aspect-ratio-mini": {}, 
"postcss-write-svg": { utf8: false }, 
"postcss-cssnext": {}, 
"postcss-px-to-viewport": { viewportWidth: 750, // (Number) The width of the viewport. 
viewportHeight: 1334, // (Number) The height of the viewport. 
unitPrecision: 3, // (Number) The decimal numbers to allow the REM units to grow to. 
viewportUnit: 'vw', // (String) Expected units. 
selectorBlackList: ['.ignore', '.hairlines'], // (Array) The selectors to ignore and leave as px. 
minPixelValue: 1, // (Number) Set the minimum pixel value to replace. 
mediaQuery: false // (Boolean) Allow px to be converted in media queries. }, 
"postcss-viewport-units":{}, 
"cssnano": { preset: "advanced", autoprefixer: false, "postcss-zindex": false }
```
* 完成
****

**参考资料 ：**
[如何在Vue项目中使用vw实现移动端适配](https://www.w3cplus.com/mobile/vw-layout-in-vue.html)