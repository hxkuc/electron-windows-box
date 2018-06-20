
## 功能介绍

electron-vue-windows的主进程api，之所以分开两个npm包是因为electron的remote.require()是根据主进程当前的js路径引入的，但是不同的webpack配置和不同的目录结构导致require引入会出问题，所以目前采用两种包的方式。

## API介绍
