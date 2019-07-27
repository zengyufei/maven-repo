在 pom.xml 引入配置

```xml
<!-- 曾玉飞 maven 个人仓库 -->
<repository>
    <id>maven-repo-master</id>
    <url>https://raw.github.com/zengyufei/maven-repo/master/</url>
    <snapshots>
        <enabled>true</enabled>
        <updatePolicy>always</updatePolicy>
    </snapshots>
</repository>

```
