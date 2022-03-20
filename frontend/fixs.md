# fix
yarn build
##  TypeError: GitRevisionPlugin is not a constructor
https://github.com/secvisogram/secvisogram/pull/44
```
npm uninstall git-revision-webpack-plugin
npm install --save-dev git-revision-webpack-plugin@5.0.0-1
<!-- npm i @ant-design/colors -->
yarn add @ant-design/colors
yarn add @ant-design/colors/lib/generate
npm ci
npm run dev

# vue.config.js
const { GitRevisionPlugin } = require('git-revision-webpack-plugin')
# config/plugin.config.js
const {generate} = require('@ant-design/colors')

# vue.config.js
# fix: https://webpack.js.org/plugins/ignore-plugin/
new webpack.IgnorePlugin({resourceRegExp:/(^\.\/locale$)|(moment$)/}),

yarn build
```

##  Cannot read property 'NormalModule' of undefined
https://stackoverflow.com/questions/70811364/typeerror-cannot-read-property-normalmodule-of-undefined
```

rm -rf node_modules
npm i -g npm
npm install
yarn install
yarn build

# This is perhaps a problem with webpack5. I fixed it with:
npm install webpack@4.39.3 --save
```