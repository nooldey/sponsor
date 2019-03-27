## 使用方法（How to use）：

``` html
<iframe src="https://zhuweisheng.com.cn/sponsor" style="width: 100%; height: 165px;border: none;"></iframe>
```

## 二次开发

+ VScode开发环境下，安装全局npm包`less`，以及vscode-plugin:`easy less`，安装完毕后，编辑less文件，将自动输出到css/目录下。

+ 无nodejs环境或不使用全局npm包，可直接编辑css/index.css文件，引入到iframe前确保icons、images、css文件夹保留以及index.html文件保留即可，其他文件可自行删减。

## 鸣谢

本项目衍生自 https://github.com/Kaiyuan/donate-page
UI设计来源donate-page项目原设计；
部分交互有所参照，代码组织为自行设计开发，相对原项目，本项目由纯html+css（less）开发完成，不引入jQuery，力求简洁效果和最少加载。