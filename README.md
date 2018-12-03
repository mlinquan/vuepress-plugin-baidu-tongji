# [vuepress-plugin-baidu-tongji](https://github.com/mlinquan/vuepress-plugin-baidu-tongji)

> Baitu tongji plugin for vuepress

## Install

```bash
yarn add -D vuepress-plugin-baidu-tongji
# OR npm install -D vuepress-plugin-baidu-tongji
```

## Usage

```javascript
module.exports = {
  plugins: ['vuepress-plugin-baidu-tongji', {
    hm: 'abcdefghijklmnopqrstuvwxyz123456'
  }]
}
```
or
```javascript
module.exports = {
  plugins: ['baidu-tongji', {
    hm: 'abcdefghijklmnopqrstuvwxyz123456'
  }]
}
```
or
```javascript
module.exports = {
  plugins: {
    'baidu-tongji': {
      hm: 'abcdefghijklmnopqrstuvwxyz123456'
    }
  }
}
```

## Options

### hm

- Type: `string`
- Default: `undefined`

Provide the Baidu Tongji ID to enable integration.
