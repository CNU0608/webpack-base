#使用方法

##1.全局安装webpack
```html
	$ cnpm install webpack -g
```

#2.进入项目
```html
	$ cnpm init
	$ cnpm install webpack jquery --save-dev
```

#3-1.打包文件
```html
	$ webpack ./js/entry.js bundle.js
```

##或者在根目录下创建webpack.config.js文件
配置代码如下：
```html
	module.exports = {
		devtool: 'source-map',
		entry: './js/entry.js',
		output: {
			path: './',
			filename: 'bundle.js'
		}
	}
```
然后执行
```html
	$ webpack
```

#运行该项目
```html
	$ cnpm install
	$ webpack
```