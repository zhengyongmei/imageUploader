# example_uploader

## 使用方法如下：
1. maxLimitWidth： 限制的最大上传宽度 
2. maxLimitHeight： 限制的最大上传高度 
3. maxSize： 图片允许的最大多少kb的图片上传 
4. img: 默认展示的图片内容 添加sync的话 修改的值会同步给父组件 

```
<Uploader :img.sync="url" maxLimitWidth="1000" maxLimitHeight="1000" />
```

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
