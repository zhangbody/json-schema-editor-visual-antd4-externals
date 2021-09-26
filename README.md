# json-schema-editor-visual-antd4-externals
A json-schema editor of high efficient and easy-to-use, base on React.

![avatar](json-schema-editor-visual.jpg)

## Usage
```
npm install json-schema-editor-visual-antd4-externals
```

```js
const option = {}
import 'antd/dist/antd.css'
require('json-schema-editor-visual-antd4-externals/dist/main.css')
const schemaEditor = require("json-schema-editor-visual-antd4-externals/dist/main.js");
const SchemaEditor = schemaEditor(option)

render(
    <SchemaEditor />,
  document.getElementById('root')
)
```

## Option Object

| name | desc | default |
| ---- | ----------- | --------- |
| `lg` | language, support `en_US` or `zh_CN` | en_US 

## SchemaEditor Props

| name | type | default | desc
| ---- | ----------- | --------- | --------- |
| `data` | string | null | the data of editor
| `onChange`| function | null | 
| `showEditor` | boolean | false | 

## Links
https://github.com/zyqwst/json-schema-editor-vue

## Change

 1. Use antd4
 2. Use lodash to replace underscore
 3. Use easy-json-schema to replace generate-schema (the object attribute of array is required by default)
 4. Remove the style of webkit-scrollbar
