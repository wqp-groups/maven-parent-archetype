# springboot-maven-parent-archetype

创建springboot maven父工程骨架

#### 1、创建骨架操作步骤
- 配置本地maven环境变量,检查mvn命令是否能正常操作

- 创建新maven工程并编写好相关的配置及代码

- 使用命令行打开工程目录

- 在命令行内执行 `mvn archetype:create-from-project`, 等待出现 `[INFO] BUILD SUCCESS`字样

- 进入到`cd target/generated-sources/archetype`目录，再执行`mvn install -Dmaven.test.skip=true`,等待出现`[INFO] BUILD SUCCESS`字样

- 打开配置的maven仓库目录，检查archetype-catalog.xml里面的内容是否正常

- 至此maven骨架生成操作结束

#### 2、添加骨架

- 新建maven工程过程中，需要`勾选 Create from archetype, 在界面右侧点击 Add Archetype按钮`

- 在弹出的Add Archetype新框中填写信息，里面的内容同上一步新建骨架时archetype-catalog.xml时面的内容保持一致，再点击ok按钮即可

