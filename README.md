# vue-i18n-sync
一键生成vue国际化配置

## 使用
安装本插件后， 选中文本，右键选择生成Vue国际化配置，支持快捷键cmd+r

注意使用前需要先配置.syncfile文件syncDirRoot，指定生成的配置目录
## 添加配置

工程下添加.syncfile
```
export default {
  // 同步生成配置的根目录
  syncDirRoot: './src/locales',
  // 同步生成配置的分类目录
  syncDirs: ['zh-CN', 'en-US', 'no-NO'],
  // 生成配置文件后缀 默认.js
  syncFileType: '.js',
  // 生成配置做间距 默认2
  syncTabWidth: 2,
  // 生成配置属性字符串 默认'
  syncQuotes: '\'',
};
```




