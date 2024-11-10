# 环境搭配  

本人通过摸索,最终的环境搭配是这样的：  
JDK：Azul Zulu 8  
IDEA：2021.2.4  
MDK：[原版MDK的一个Fork](https://github.com/anatawa12/ForgeGradle-1.2)  

**在现在,强烈不建议使用原版 Forge MDK！除非你非常确定你需要这么做。**（因为你永远不知道现在缺了什么老版本开发需要的东西）  

# 环境基本搭建  

现在,先不要急着打开 Intellij IDEA。  
打开你的终端（笔者这里是 Linux 环境）,输入：  
```bash
./gradlew setupDecompWorkspace idea
```
一般来说此步骤会消耗大量的内存（但实际上4GB的内存就能轻松抗住了）
当看见`BUILD SUCCESSFUL`之后,打开 Intellij IDEA,然后导入此项目,开始你的老版本开发之旅吧！