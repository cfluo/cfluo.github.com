# cfluo.github.com
个人主页
http://www.cnblogs.com/AloneSword/p/4883472.html
// 克隆 parent
git clone https://github.com/mybatis/parent.git
// 将该项目安装到本地maven库, mybatis-generator依赖于该项目
mvn clean install -Dmaven.test.skip=true
// 克隆 mybatis-generator
git clone https://github.com/mybatis/generator.git
// 将该jar安装到本地, 之后项目中使用, 时间有点长, 可以喝杯咖啡
mvn clean install -Dmaven.test.skip=true
