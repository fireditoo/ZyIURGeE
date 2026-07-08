# 前言

随着新冠疫情的全球爆发，社区疫情管理成为了重中之重。为了便于社区管理者对疫情进行有效监控和管理，我们开发了一款社区疫情管理系统。本项目使用Java语言，结合Spring Boot框架、MySQL数据库等技术进行开发。以下是本项目的详细介绍。

## 内容介绍

社区疫情管理系统是一款集疫情数据管理、信息发布、居民健康档案管理等功能于一体的系统。主要功能包括：疫情数据实时展示、疫情资讯发布、居民健康状况上报、疫情排查管理、统计分析等。通过本系统，社区管理者可以快速掌握疫情动态，高效开展疫情防控工作。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、css3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是一段疫情数据实时展示的核心代码：

```java
// 查询疫情数据
@RequestMapping(value = "/getEpidemicData", method = RequestMethod.GET)
public ResponseEntity<List<EpidemicData>> getEpidemicData() {
    List<EpidemicData> dataList = epidemicDataService.getEpidemicData();
    return new ResponseEntity<>(dataList, HttpStatus.OK);
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/286206/18/22124/103884/689e177eF6d0f7642/56ef9b5a33a0c5f4.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/310399/26/26702/26198/689e1761Fc0be8ace/fc38e67acfc9f09f.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/311368/10/26026/37811/689e1761F59f5497e/fb6a9ab403a73d56.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/315297/1/25848/25170/689e1762F363aaed4/76f422b3800e1fdd.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/326769/37/4638/34308/689e1762Fbddeb321/949ea28f72dde6b2.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/316231/25/26134/24883/689e1763Ffa76ed2d/a2e89106456e5035.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/309437/9/26683/40593/689e1763F5f97a833/0361dd5869dcf6b1.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/288959/8/14436/29982/689e1764F75d23339/4ac7c0259394e57f.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/308915/7/26404/52536/689e1764F3bcec06e/32b436e62671176a.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/290646/21/20939/43369/689e1765F6b0b8a1a/55102431a0d72234.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
