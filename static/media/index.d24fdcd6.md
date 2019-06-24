## 开发指南
致力于提供给程序员愉悦的开发体验

>正确安装和配置了 Node.js v8 或以上。官方指南假设你已了解关于 HTML、CSS 和 JavaScript 
的中级知识，并且已经完全掌握了 React 全家桶的正确开发方式。

### 安装
```js
推荐使用 npm 的方式安装，它能更好地和webpack打包工具配合使用

npm install element-react --save

npm install antd --save
```
---

### 特性
- 提炼自企业级中后台产品的交互语言和视觉风格。
- 开箱即用的高质量 React 组件。
- 全链路开发和设计工具体系。
---

## 使用
```js
import React from 'react';
import ReactDOM from 'react-dom';
import { Button } from 'element-react';

import 'element-theme-default';

ReactDOM.render(<Button type="primary">Hello</Button>, document.getElementById('app'));
```

