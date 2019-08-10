# fe-vue-preset
使用 preset 初始化vue项目, 配合vue/cli使用
# usage
```
npm install -g @vue/cli

# 使用 preset 初始化项目
git clone git@github.com:AlexZ33/fe-vue-preset.git

vue create --preset ./fe-vue-preset

# 安装全局依赖
npm install -g eslint stylelint commitizen

# 安装项目依赖
npm install --save es6-promise@4.1.1 axios@0.18.0 vue@2.5.17 vue-router@3.0.2 raven-js@3.27.0 normalize.css@8.0.1 && npm install --save-dev stylelint-config-standard postcss-px2rem html-webpack-inject-attributes-plugin mini-css-extract-plugin vue-template-compiler@2.5.17 glob shelljs  webpack assets-webpack-plugin compression-webpack-plugin @gfx/zopfli husky cz-customizable @commitlint/config-conventional @commitlint/cli

```
