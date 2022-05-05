# javafx-boot

#### 介绍
JavaFx+SpringBoot快速开始脚手架，应用示例。非SpringBoot版本请移步至该仓库：https://gitee.com/westinyang/javafx-start

> 参考资料：https://segmentfault.com/a/1190000014037443

Maven插件
- [springboot-javafx-support](https://github.com/roskenet/springboot-javafx-support)
- [JavaFX Maven Plugin](https://github.com/javafx-maven-plugin/javafx-maven-plugin)

#### 配置（application.yml）

```yaml
javafx:
  title: JavaFx & SpringBoot
  appicons: /icon/icon.png
  stage:
    width: 640
    height: 480
#    style: DECORATED  # javafx.stage.StageStyle [DECORATED, UNDECORATED, TRANSPARENT, UTILITY, UNIFIED]
#    resizable: false
```

#### 运行效果

![截图](./screenshot/03.gif)

#### 打包教程

`mvn jfx:native`

#### 参与贡献

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request
