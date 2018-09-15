[toc]
#flow配置
1. Setup Compiler

```
npm install --save-dev babel-cli babel-preset-flow
```
添加.babelrc 文件，内容为：

```
{
  "presets": ["flow"]
}
```
2. 安装flow

```
 npm install -g flow-bin
```
3. 初始化项目

```
 npm run flow init
```
此命令是为了初始化项目，在项目中添加了`.flowconfig`, 如果手动添加`.flowconfiig` 文件,则不需要在额外执行`npm run flow init`命令了
.flowconfig 中内容如下：

```
[ignore]

[include]

[libs]

[lints]

[options]

[strict]
```

当然 也可以根据其中的配置选项自定义配置了

具体用法请参flow官方文档：https://flow.org/en/docs/getting-started/