# CakesShop

**作者：积极向上小木木 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;联系方式：PositiveMumu@126.com**

*基于jsp+servlet的网上蛋糕商城*

## 一、项目功能

### 1.前台功能
1. 商品基本展示,包括推荐商品展示和类型商品展示.
2. 推荐商品包括条幅推荐,热销推荐和新品推荐.
3. 按照商品类型展示商品.
4. 商品详细信息展示.
5. 商品加入购物车.
6. 修改购物车内商品信息,例如数量等.
7. 用户登录.
8. 用户注册.
9. 修改个人信息,包括密码和收获信息.
10. 购物车付款.
11. 用户订单查询.
12. 根据关键字搜索商品.

### 2.后台功能

*当管理员用户登录后会显示后台管理按钮,点击介意进入后台管理页面*

1. 订单操作:包括按状态查询订单,修改订单状态(发货,完成,删除).
2. 用户操作:包括查询所有用户,新增用户,修改用户密码,修改用户信息和删除用户.
3. 商品类目操作:包括查看所有类目,增加商品类目,修改商品类目信息以及删除商品类目.
4. 商品操作:包括查询所有商品,新增商品,修改现有商品信息以及删除商品.

*注意,删除用户时需要先删除用户下的所有订单，才可以删除用户。删除商品类目时，要先删除类目下的商品，才能删除商品类目。删除商品时，可直接删除，他的推荐信息也会直接删除!（不要问为什么做的这么蠢，当时脑子抽风了！）*

## 二、项目开发环境
1. 项目使用IDEA 2017.3.5进行开发。
2. Tomcat版本为 8.5.42。
3. 数据库为mysql 5.7。
4. JDK版本为1.8_211。
5. 开发过程中使用到插件有从c3p0,DButil,Beanutil,Fileupload,Jstl等,jar包版本详见/web/WEB-INF/lib目录.

## 三、项目还原设置
1. 在本地或服务器上安装mysql数据库(如果版本较高请考虑更新数据库连接驱动)。

2. 将cakeshop.sql文件还原至数据库中。

3. 在CookieShop/src/c3p0-config.xml中的文字替换，主要有连接字符串，用户名和密码。

4. 使用IDEA打开项目并重新指定jdk。

5. 下载Tomcat并在IDEA中配置。

6. 运行项目。

## 四、项目截图

### 1.用户界面

1. 主页：

![mark](http://image.vilicode.com/blog/20191007/Nbm52VHFdzm8.png?imageslim)

2. 按类目查询商品：

![mark](http://image.vilicode.com/blog/20191007/C0KhTUu8ooBV.png?imageslim)

3. 热销商品：

![mark](http://image.vilicode.com/blog/20191007/hxMNcwMKU0FN.png?imageslim)

4. 新品商品：

![mark](http://image.vilicode.com/blog/20191007/IM8Do47kmb5t.png?imageslim)

5. 商品详细信息：

![mark](http://image.vilicode.com/blog/20191007/RY7GO8Wipwo1.png?imageslim)

6. 注册：

![mark](http://image.vilicode.com/blog/20191007/eMnTQAL75Vt5.png?imageslim)

7. 登录：

![mark](http://image.vilicode.com/blog/20191007/JGSwTm2mrSqe.png?imageslim)

8. 个人中心：

![mark](http://image.vilicode.com/blog/20191007/49cCVEIWxEMY.png?imageslim)

9. 我的订单：

![mark](http://image.vilicode.com/blog/20191007/dSD1yzYfd7jM.png?imageslim)

10. 购物车：

![mark](http://image.vilicode.com/blog/20191007/yvCKvdft7PDs.png?imageslim)

11. 搜索商品：

![mark](http://image.vilicode.com/blog/20191007/IzQvnWBpGsNY.png?imageslim)

### 2.后台界面

1. 订单管理：

![mark](http://image.vilicode.com/blog/20191007/qncenLMph5cI.png?imageslim)

2. 用户管理：

![mark](http://image.vilicode.com/blog/20191007/QonqAatC7AKF.png?imageslim)

3. 商品类目管理：

![mark](http://image.vilicode.com/blog/20191007/rpfitJTGFToy.png?imageslim)

4. 商品管理：

![mark](http://image.vilicode.com/blog/20191007/iA7qFzPDCl9t.png?imageslim)

5. 新增商品：

![mark](http://image.vilicode.com/blog/20191007/grDUX6ulyVhi.png?imageslim)
