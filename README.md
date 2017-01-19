# GradleDemo
使用config.gradle文件统一管理所有的子module的依赖包，版本号，编译版本等信息，方便升级
统一管理每一个module的gradle文件
1. 版本号，编译版本等
2. 依赖包的统一
3. 配置过程如下：
  ● 在项目的根目录下创建一个config.gradle文件，该文件就是统一配置gradle，可以在所有的子module中使用。

  ● 在config.gradle中编写共性内容

  ● 在根目录的build.gradle中应用这个config.gradle

  ● 在子module中的build.gradle中去引用



