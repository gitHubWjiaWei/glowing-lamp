# glowing-lamp
尚硅谷在线学堂
##### 项目介绍：
**在线教育核心模块：**学习课程部分

​	项目采用前后端分离部分。

​	**后端技术：**

​		SpringBoot。

​		SpringCloud。

​		Spring Securitr

​		MybatisPlus。

​		redis，

​		maven，

​		easyExcel，

​		jwt，

​		QAuth2



​	前端技术：

​	vue+element-ui，axios，nodejs

​	

​	其他技术：

​	阿里云：OSS。

​	阿里视频点播服务。

​	阿里短信服务。

​	微信支付和登录。

​	docker，

​	git，

​	jenkins

##### 商业模式：

​	**B2C：**

​		角色：普通用户，管理员。

​		管理员功能：添加，删除，修改，查看。

​		普通用户：查询。

​	**B2B2C:**

​		商家对商家对用户模式。

##### 项目功能：

​	B2C模式：

​		**系统后台（管理员）：**

​			1.讲师管理模块：

​			2.课程分类管理模块：

​			3.课程管理模块：

​				1.视频

​			4.统计分析：

​				1.查看课程观看和购买量。

​				2.查看注册人数

​			5.订单管理：

​			6.banner管理：

​			7.权限管理

​		**系统前台（用户）：**

​			1.首页数据显示：

​			2.讲师列表

​			3.课程列表

​			4.登录注册

​			5.扫码登录

​			6.扫码支付


#### 依赖导入：
```xml
<dependencies>
        <!-- https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-test -->
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-test</artifactId>
            <version>2.3.4.RELEASE</version>
            <scope>test</scope>
        </dependency>
        <!-- https://mvnrepository.com/artifact/org.springframework/spring-test -->
        <dependency>
            <groupId>org.springframework</groupId>
            <artifactId>spring-test</artifactId>
            <version>5.2.9.RELEASE</version>
            <scope>test</scope>
        </dependency>

        <dependency>

        <groupId>org.springframework.boot</groupId>

        <artifactId>spring-boot-starter-test</artifactId>

        <scope>test</scope>

        <exclusions>

            <exclusion>

                <groupId>org.junit.vintage</groupId>

                <artifactId>junit-vintage-engine</artifactId>

            </exclusion>

        </exclusions>

    </dependency>

        <!--mybatis-plus-->
        <dependency>
            <groupId>com.baomidou</groupId>

            <artifactId>mybatis-plus-boot-starter</artifactId>

            <version>3.0.5</version>

        </dependency>
    <!--mybatis-plus-->



    <!--mysql-->

        <dependency>
            <groupId>mysql</groupId>
            <artifactId>mysql-connector-java</artifactId>
            <version>8.0.23</version>
        </dependency>

        <!--lombok用来简化实体类-->

    <!-- https://mvnrepository.com/artifact/org.projectlombok/lombok -->
    <dependency>
        <groupId>org.projectlombok</groupId>
        <artifactId>lombok</artifactId>
        <version>1.18.32</version>
        <scope>provided</scope>
    </dependency>
        <dependency>
            <groupId>junit</groupId>
            <artifactId>junit</artifactId>
            <version>4.12</version>
            <scope>test</scope>
        </dependency>
        <dependency>
            <groupId>org.junit.jupiter</groupId>
            <artifactId>junit-jupiter</artifactId>
            <version>RELEASE</version>
            <scope>test</scope>
        </dependency>
    </dependencies>
```
