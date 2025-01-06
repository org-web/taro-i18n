# Taro 示例

## 安装依赖
```
yarn install 
```

## 编译运行

开发：本地调试

开发环境
```
yarn dev:weapp 
```

打包：体验版

开发环境
```
yarn build:dev
```

## 编译运行之后把项目文件夹下的dist文件夹加载到微信小程序开发工具即可

微信小程序开发工具下载：https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html

## Taro 版本升级

- 使用Taro 升级命令更新CLI版本到最新版本
```
taro update self
```

- 使用Taro 升级命令更新CLI版本到指定版本
```
taro update self [版本号]
```

- 使用Taro 升级命令将项目依赖升级到与@tarojs/cli一致的版本
```
taro update project
```

- 使用Taro 升级命令将项目依赖升级到指定版本
```
taro update project [版本号]
```
