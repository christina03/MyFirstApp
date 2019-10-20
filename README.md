# MyFirstApp
My first react native app

## 使用介绍

> 注意：此介绍针对的是Mac环境

### 1、安装依赖

必须安装node、watchman、React Native命令行工具、Xcode。运行ios版本时，需要cocoapods，所以也需要安装。

#### （1）先安装HomeBrew

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

##### （2）安装其他

```
brew install node //已安装node的不需要，检查其版本是否为v10以上
brew install watchman
sudo gem install cocoapods

```
##### （3）Yarn、React Native 的命令行工具安装

```
npm install -g yarn react-native-cli
```

### 2、初始化项目

#### （1）初始化

```
react-native init MyFirstApp
```
#### (2)运行

```
cd MyFirstApp
react-native run-ios
```