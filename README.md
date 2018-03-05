# ecaray-cli

## Installation

```
npm install ecaray-cli -g
```

## Usage

Open your terminal and type `ecaray` or `ecaray -h` , you'll see the help infomation below:

```
  Usage: ecaray <command>

  Commands:
    add      新增模板
    list     查看已添加模板
    init     初始化模板并创建新项目
    delete   删除已存在模板

  Options:
    -h, --help     output usage information
    -V, --version  output the version number
```

## ecaray add

1. Set the custom name of the template: projects-merge(自定义模板)
2. Owner/name of the template: wqb2017/projects-marge(github 模板)
3. Branch of the template: master(选中的分支)

## ecaray init

1. Template name: projects-merge(初始化自定义模板)
2. Project name: qianqianjinfu(创建项目名称)
3. Where to init the project: ./ (创建项目存储地址)

## ecaray delete

1. Which template you want to delete: projects-merge(删除模板)
