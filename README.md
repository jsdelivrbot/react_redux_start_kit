# react_redux_start_kit

專案開發框架與其環境設定，包含基礎程式範例。

# version
1. nodeJS v6.3.0
2. npm v3.10.3

## 設計核心       

- 多人多工開發模式：    
模組化程式，開發者僅需維護自己負責的 container

- 簡化的配置：    
定義設定檔(config.js)快速定義 reducer、router 與 API

## 開始使用

### 線上看
[第四版](https://github.com/mega-media/react_redux_start_kit/tree/4.0.0-beta)-
[文件](http://arshown.mega99.net:8080/startkit/v4)

[第三版](https://github.com/mega-media/react_redux_start_kit)-
[文件](http://arshown.mega99.net:8080/startkit/v3)


### 下載專案

````
git clone git@github.com:mega-media/react_redux_start_kit.git
````

### 安裝
````
cd react_redux_start_kit
npm install
````

### 執行
````
npm start
````

開啟你常用的瀏覽器，並前往 http://127.0.0.1:8888 即可看到執行成果
> `npm start`預設執行的模式為develop，假如port 8888已被使用，可至`./config/env/dev.js`變更


### production 版本
````
npm run production
````
將專案壓縮、編碼並移除註解與console
