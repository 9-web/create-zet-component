### create zet 脚手架
zet-component 通过 [create-zet](https://github.com/9-web/create-zet) 提供脚手架能力，包含：
* zc doc 快速生成文档模板

### 安装
```
(yarn || npm) install create-zet -g
```

### 使用
* `cz doc -n Component -f index.mdx --d /usr/bin --m resource`


### 参数
* -n, --name 组件名称,默认值Component
* -m, --menu 文档菜单,默认值Other
* -f, --file 文件名称,默认值index.mdx
* -d, --dir 文件目录地址,默认值当前运行环境目录
* -h, --help 帮助信息
