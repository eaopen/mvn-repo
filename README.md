# mvn-repo

已提交到maven center中。

group = io.github.eaopen

如使用github maven需要配置github public token。  
https://maven.pkg.github.com/eaopen/mvn-repo

## 配置maven参考

项目pom.xml 添加 repository id=github-mvn-openea
```
    <repositories>
        <repository>
            <id>github-mvn-openea</id>
            <name>github-openea</name>
            <url>https://maven.pkg.github.com/eaopen/mvn-repo</url>
            <releases>
                <enabled>true</enabled>
            </releases>
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </snapshots>
        </repository>
    </repositories>
```

maven本地配置 conf/settings.xml
```
  <servers>
     <server>
        <id>github-mvn-openea</id>
        <username>eaopen</username>
        <password>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</password>
      </server>
  </servers>
```


# 参考

maven public token

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

expired:
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
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
